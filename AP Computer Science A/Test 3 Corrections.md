[[APCSA]]

8.
	Correct: F 
	Explanation: The array must hold the imported type so instead of boolean, it should be Boolean.
	
9.
	Correct: F
	Explanation: Since the arraylist is holding string values, it cannot hold the type with higher hierarchy
	
20.
	Correct: A
	Explanation: It initializes an array without filling it with null or default values.
	
23.
	Correct: C
	Explanation: Since the first line gets the index of the first value with fish in it, it will remove that value and the one after it.

28.
```java
public ArrayList<String> extract (ArrayList<String> list) {
	ArrayList<String> newList = new ArrayList<String>();
	int i = 0;

	while (i < list.size()) {
		String temp = list.get(i);
		if (temp.length <= 5) {
			newList.add(temp);
			list.remove(i);
		} else {
			i++;
		}
		
	}
}

```