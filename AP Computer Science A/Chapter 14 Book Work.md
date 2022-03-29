1) Pattern recognition searches multiple indexes, while searching only searches one index

6) a) 7 b) 8

8)
```java
public static int search (int[] a, int m, int n, int target) {
	if (m >= n) {return -1;}
	
	int middle = (m + n) / 2;

	if (a[middle] == target) {
		return middle;
	}

	if (a[middle + 1] == target) {
		return middle + 1;
	}

	int bottomIndex = search(a, m, middle - 1, target);

	if (bottomIndex != -1) {
		return bottomIndex;
	} else {
		return search(a, middle + 1, n, target);
	}
```

9)

10)

11)

12)

13)

14)

