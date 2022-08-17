``  
# Chapter 19
1)
	a) T
	b) F
	c) F
2)
	a) O(n<sup>2</sup>)
	b) O(n)
	c) O(n<sup>2</sup>/2)
3) c
7)
	a) always
	b) sometimes
	c) never

# Chapter 21
1) all should have "head"
2) count
3)
```java
if(head == null)
        return null;
    else{
        ListNode temp = head;
        head = head.getNext();
        temp.setNext(null);   
        size--;
        return temp.getElement();
    }
}
```
4)
```java
public int size()
{
    int size = 0;
    Node CurrNode = head;
    while(CurrNode.next != null)
    {
        CurrNode = CurrNode.next;
        size++;     
    }
    return size;
}
```
5)
```java
public static Node add(Node header, Object x) {
       // save the reference to the header so we can return it.
       Node ret = header;

       // check base case, header is null.
       if (header == null) {
           return new Node(x, null);
       }

       // loop until we find the end of the list
       while ((header.next != null)) {
           header = header.next;
       }

       // set the new node to the Object x, next will be null.
       header.next = new Node(x, null);
       return ret;
   }
```
6) i dont know this one
7)
```java
public static String FindConcat(Node head) {
    String s = "";
    if(head == null) return s;
    else if(head.next = null) {
        s += head.data;
        return s;
    }
    else {

    }

}
```
# Chapter 22
1)
	a) T
	b)F
	c)T
2)
```java
public static Node add(Node header, Object x) {
       // save the reference to the header so we can return it.
       Node ret = header;

       // check base case, header is null.
       if (header == null) {
           return new Node(x, null);
       }

       // loop until we find the end of the list
       while ((header.next != null)) {
           header = header.next;
       }

       // set the new node to the Object x, next will be null.
       header.next = new Node(x, null);
       return ret;
   }
   public static String FindConcat(Node head) {
    String s = "";
    if(head == null) return s;
    else if(head.next = null) {
        s += head.data;
        return s;
    }
    else {

    }

}
```
3)
```java
public void isEmpty(not possible){
	somehow this doesn't work
}
```
6)
	a) Yes
	b) The stack could be exploited
	c) 
```java
public char push (char ch) {
	stack += ch;
}
public char pop() {
	return stack[1];
}
```

	d) cant


# Chapter 24
1)
	root: top of tree
	parent: node that has the children
	child: under parent
	ancestor: far relative of parent
	leaf: child
	subtree: everything after a specific node
2)
	10
3)
	a) 5
	b) 7
4) no math
6)
```java
public boolean isLeaf(TreeNode root) {
	if(node.hasNext()){
		return false;
	} else { return true; }
} 
```
7)
```java
public int sumTree(TreeNode root) {
	root.getNext() += count;
	return count;
}
```
8)
number of nodes

