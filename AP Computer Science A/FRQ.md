1a)

```java
public boolean simulate() {
	int maxHopDist = 0;
	for (int i = 0; i < maxHops; i++) {
		int hopDist = hopDistance();
		maxHopDist += hopDist;
		if (maxHopDist >= goalDistance) {
			return true;
		} else if (maxHopDist < 0) {
			return false;
		}
		return false;
	}
}

```

1b) 

4a) 

```java
public static int[] getColumn (int[][] arr2D; int c) {
	int[] returnable = new int[arr2D.length];
	for (int i = 0; i < arr2D.length; i++) {
		returnable[i] = arr2D[i][c];
	}

	return returnable;
}
```

4b)
```java
public static boolean isLatin(int[][] square) { 
	if (containsDuplicates(square[0])) { return false; } 
	for (int r = 1; r < square.length; r++) { 
		if (!hasAllValues(square[0], square[r])) { return false; } 
	} 

	for (int c = 0; c < square[0].length; c++) {
		if (!hasAllValues(square[0], getColumn(square, c))) { return false; } 
	} 
	return true; 
}
```