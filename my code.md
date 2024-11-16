
	int x;
 
	cout << "\n[1](seafood)----> Avalable\n";
	cout << "\n[2](grill)-----> Avalable\n";
	cout << "\n[3](salads)****\n";
	cout << "\n[4](meat)****\n";
	cout << "\nchoose your food-type number : ";
	cin >> x;
 
	if (x==1)
	{
		int y;
		cout << "\n[1](tuna)\n";
		cout << "\n[2](octpos)\n";
		cout << "\n[3](salmon)\n";
		cout << "\n[4](shrimp)\n";
		cout << "\nchoose your dish number : ";
		cin >> y;
		switch (y)
		{
		case 1:
			cout << "\ntuna\n";
			break;
		case 2:
			cout << "\noctpos\n";
			break;
		case 3:
			cout << "\nsalmon\n";
			break;
		case 4:
			cout << "\nshrimp\n";
			break;
		}
	}
	if (x == 2)
	{
		int z;
		cout << "\n[1](Chicken-teppenyaki)\n";
		cout << "\n[2](Beef-teppenyaki)\n";
		cout << "\n[2](Yasai-teppenyaki)\n";
		cout << "\nchoose your dish number : ";
		cin >> z;
		switch (z)
		{
		case 1:
			cout << "\nChicken-teppenyaki\n";
			break;
		case 2:
			cout << "\nBeef-teppenyaki\n";
			break;
		case 3:
			cout << "\nYasai-teppenyaki\n";
			break;
		}
	}
	else
	{
		cout << "\nerror occured\n";
	}
   return 0;
}
