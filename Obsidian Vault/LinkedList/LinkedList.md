## LinkedList -> List which is similar to Array but instead of index we have node(val: type)

### simple implementation of LinkedList:

func reverseLinkedList(head: ListNode?) -> ListNode? {
	var currentNode = head
	 var prev = (ListNode?(nil))
	 while currentNode != nil {
		let next = currentNode?.next
		currentNode?.next = prev
		prev = currenNode
		currentNode = next
	  }
	 return prev
}

## Dont forget that LinkedList is optional type and use unwrapping either force or not 

## Most questions are  solved by pointers
