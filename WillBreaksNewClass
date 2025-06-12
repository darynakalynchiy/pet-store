@isTest
public class WillBreaksNewClassNewClass {

  Integer newField;

  public WillBreaksNewClass(Integer value){
    newField = value;
  }

  private void unusedMethod(){}

  /*
  * This is fine. Will said so.
  */
  public boolean isBadExample(){ 
    return true; 
  } 

  
  public void terribleCode(Integer param){
    param =1;
  }

  public static void triggerBasicAuraHandledError() {
    try {
      integer a = 1 / 0; // Division by zero causes exception
    } catch (Exception e) {
        // "Convert" the exception into an AuraHandledException
      throw new AuraHandledException('THIS IS THE ERROR MESSAGE');
    }
  }
  
    @isTest static void onlyTest(){
        triggerBasicAuraHandledError();
  	}
}
