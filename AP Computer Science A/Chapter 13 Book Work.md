1)
```java
	public int product (int a, int b) {
		return product(a, b-1) + a;
	}
```
2)
18
3)
VEHA UNF
4)
```java
public int findMin(int[] list, int n) {
	int min = 0;
	if (n = 1) {
		min = list[0];
	} else if (list[n] < list[n-1]) {
		n--;
		findMin(list, n);
	}
}
```
5)
a, b, g
7)
it would never
9)
030
11) 9
13) 
