class staticExample
{ 
  StaticExample()
  {
    System.out.println("This is a constructor");
  }
  static void example()
  {
     System.out.println("hello this is a static function");
  }
  void instance_example()
  {
     System.out.println("this is a instance function example");
  }
  public static void main(String args[])
  {
     staticExample se=new staticExample();
     static_example();
     se.instance_example();
  }
}
