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