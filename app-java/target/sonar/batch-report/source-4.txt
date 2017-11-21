package example;

public class HelloWorld {

  public void coveredByUnitTest() {
	AlexaExample obj;
	
	if(obj != null){
	}
	
	obj.example();
	
    System.out.println("coveredByUnitTest1");
    System.out.println("coveredByUnitTest2");
  }

  public void coveredByIntegrationTest() {
    System.out.println("coveredByIntegrationTest1");
    System.out.println("coveredByIntegrationTest2");
    System.out.println("coveredByIntegrationTest3");
  }

  public void notCovered() {
    System.out.println("notCovered");
  }

}
