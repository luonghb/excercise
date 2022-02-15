//Bài 1: Tính S(n) = 1 + 2 + 3 + … + n.

//Cách 1: Dùng vòng lặp:
int SumOfNum(int n)
{
	int sum = 0;
	while(n > 0)
	{
		sum += n--;
	}
	return sum;
}
// Cách 2: Dùng công thức tính tổng:
int SumOfNum2(int n)
{
	return n * (n + 1) * 0.5;
}
