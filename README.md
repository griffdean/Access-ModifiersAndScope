# Access-ModifiersAndScope

Scope is the code within the brackets.
For example, the scope of the following:
void function() {
  if(true){
    print(x);
  }
  else{
    print(y);
  }
}
//scope of the function is the if-else statement

void function() {
  if(true){ <-------- //scope is just the if statement 
    print(x);
  }
  else{
    print(y);
  }
}

Access modifiers are either public or private. Public means that it has access to everything such as other scripts. Private means it is confined to just that script, restricted access.
For example,
public int coins = 0;
//access to everything, default is 0, can change within unity

int coins = 10;
int count = 10;
int stairs = 10;
//default is private if you don't declare the datatype, and value is 10

private int coins = 5;
//can also declare it private, but dont have to

