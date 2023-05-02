#include <iostream>

using namespace std;

int main() 
{
{
    int a, n, m, i, j, s;
        array = a[5][5], n, m;
        cin >> n >> m >> a >> s >> i >> j;

    for (int i = 0; i < n; i++)
       for (int j = 0; j < m; j++)
            cin >> array[i][j];
    int max = array[0][0];

    for (int i = 0; i < n; i++)
        for (int j = 0; j < m; j++)
            if (array[i][j] > max)
            {
                max = array[i][j];
            }

    for (int i = 0; i < n; i++)
    {
        for (int j = 0; j < m; j++)
        {
            cout << array[i][j] << " ";
        }
        cout << endl;
    }
    cout << "Max is = " << max;
}
	
	for (int i = 0; i < n; i++)
		s += a[i][i];
	cout << "Sum of main diagonal = " << s;
	for (int i = 0; i < n; i++)
		delete[] a[i];
	delete[] a;
	return 0;
}
