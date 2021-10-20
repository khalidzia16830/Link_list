
#include <iostream>

using namespace std;
class Node{
    public:
    int data;
    Node*next;
};
int main()
{
    cout<<"Link list"<<endl;
   Node * head;
   Node * second;
   
   head = new Node();
  second= new Node();
   
   
   head->data = 12;
   head->next = NULL;
   
   second->data = 13;
   second->next = NULL;
   
   cout << "head data "<<head->data<< endl;
   cout << "second data "<<second->data<< endl;
    return 0;
}
