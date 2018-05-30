2 Add Two Numbers
在做第二题时候，接触python链表的概念  
'''
#Create ListNode：  
class ListNode:  
    def __init__(self, x):  
    self.val = x  
    self.next = None  
          
idx = ListNode(3)  
print(idx.val)  
idx.next = ListNode(4)  
print(idx.next.val)  
idx.next.next = ListNode(2)    
print(idx.next.next.val)    
    
idx2 = ListNode(4)      
print(idx2.val)     
idx2.next = ListNode(6)   
print(idx2.next.val)    
idx2.next.next = ListNode(9)    
print(idx2.next.next.val)   
idx2.next.next.next = ListNode(9)   
print(idx2.next.next.next.val)   
'''  
