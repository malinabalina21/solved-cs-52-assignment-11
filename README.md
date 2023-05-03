Download Link: https://assignmentchef.com/product/solved-cs-52-assignment-11
<br>
<strong>part_a : Fuller NodeList</strong>

<h3>Building upon the the ListNode/List code I would like you to extend the interface of a list to have these member functions as well.</h3>

struct ListNode{int element;ListNode *next;}

1. Write a function to concatenate two linked lists. Given lists l1 = (2, 3, 1) and l2 = (4, 5), after return from concatenate(l1,l2) the list l1 should be changed to be l1 = (2, 3, 1, 4, 5). Your function should not change l2 and should not directly link nodes from l1 to l2 (i.e. the nodes inserted into l1 should be copies of the nodes from l2.)

void concatenate(Node*&amp; h1, Node* h2);

<pre>// <strong>Precondition:</strong> h1 and h2 are head pointers of linked lists. The lists may be empty or non-empty.// <strong>Postcondition:</strong> A copy of list h2 is concatenated (added to the end) of list h1. List h2 should be unchanged by the function. // <strong>NOTE:</strong> The nodes added to the list h1 must be copies of the nodes in list h2.2. Write a function to insert a number as the new ith node of a linked list. Nodes initially in positions i, i+1, ..., n should be shifted to positions void insertith(Node*&amp; head_ptr, int value, size_t i);</pre>

void insertith(Node*&amp; head_ptr, int value, size_t i);

<pre>// <strong>Precondition:</strong> head_ptr is the head pointer of a linked list. The list may be empty or non-empty. // <strong>Postcondition:</strong> The number value is inserted as the ith member of the list head_ptr. If the list head_ptr has fewer than i-1 nodes in it, then value is inserted as the last node in the list.</pre>

3. Write a function to remove duplicate entries in a linked list. For example, given the list (5, 2, 2, 5, 3, 9, 2) as input, your function should change the list so that on return from the function it contains (5, 2, 3, 9).

void removeDups(Node*&amp; head_ptr);

// <strong>Precondition:</strong> head_ptr is the head pointer of a linked list. The list may be empty or non-empty.  // <strong>Postcondition:</strong> Each node in the list must have a unique element value.

<ul>

 <li>Your submission should follow this organization, all of which have been provided:

  <ul>

   <li>part_a

    <ul>

     <li>List.cpp</li>

     <li>List.h</li>

     <li>ListDriver.cpp</li>

     <li>ListNode.cpp</li>

     <li>ListNode.h</li>

     <li>Settings.h</li>

    </ul></li>

  </ul></li>

</ul>

5/5 - (2 votes)