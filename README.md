# Mission5
public class Mission5 {
   
    public static void mathematics (){
        
        List <Integer> input = new List <Integer> {12, 20, 30, 17};
        
        	for (Integer multiple : input) {
                
                String display1 = 'Ding';
                String display2 = 'Dong';
                String display3 = 'DingDong';
                
				if (math.mod (multiple,3) == 0 && math.mod (multiple,5) == 0){
                    system.debug(display3);
                }
                
                else if (math.mod (multiple,3) == 0){
            		system.debug(display1);
                }
                
                else if (math.mod (multiple,5) == 0){
                    system.debug(display2);
                }
                
                else {
                    system.debug(multiple);
                }	
            
        }
        
    }
    
}    
