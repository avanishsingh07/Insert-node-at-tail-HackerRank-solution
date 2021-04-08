# Insert-node-at-tail-HackerRank-solution
Insert node at tail HackerRank solution

static SinglyLinkedListNode insertNodeAtTail(SinglyLinkedListNode head, int data) {
        SinglyLinkedListNode node = new SinglyLinkedListNode(data);
        if(head == null){
            head = node;
            return head;
        }
        SinglyLinkedListNode temp = head;
        while(null!=temp.next){
            temp=temp.next;
        }
        temp.next=node;
        return head;
    }
    
    
    
