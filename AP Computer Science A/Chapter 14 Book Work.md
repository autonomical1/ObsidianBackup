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
10)
Yes, it is, because the data will first need to be sorted in ascending or descending order and then input into the method

11)
	a) T, because (20*(19))/2 = 190
	b) T
12)
	6, 9, 10, 22, 81, 74
13)
	3, 7, 6, 4, 1, 3, 5, 1, 2, 3, 4

14)
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

