[[APCSA]]

1a) F

1b) F

1c) T

1d) T

1e) T

3a) Y

3b) Y

3c) T

3d) F

5)

```java
public abstract class Poem {
	private int lines;

	public abstract int numLines();

	public abstract int getSyllables(int k);

	public void printRhythm() {
		String str = "";

		for (int i = 0; i < getSyllables(i); i++) {
			if (i == getSyllables(i) - 1) {
				str += "ta";
			} else {
				str += "ta-";
			}

			str += "\n";
		}

		System.out.println(str);
	}
}
```

14)

```java
public boolean sameDistance (Place p1, Place p2, Place p3) {
	return p1.distance(p2) == p1.distance(p3);
}
```