# Marble-Sorter
This Sorts marbles


What you need to do
Look at the Top 4 values of the Marble Sorter - wood, clear, tin, steel
Change those values to what is outputted by the LineFollower

You may also want to modify this function:
int getCup(int value)
{
	if (abs(value-clear) < 100)
		return 1;
	if (abs(value-steel) < 100)
		return 2;
	if (abs(value-tin) < 100)
			return 3;
	if (abs(value-wood) < 100)
			return 4;
	return 1;
}

Change 100 to the tolerance range you want:
eg: If I read values inbetween 2200 and 2500 for wood, the value of wood is 2300 and it's tolerance is is 100
