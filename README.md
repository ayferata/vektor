# vektor
import java.util.Vector; 
public class VectorExample { public static void main(String[] args) { 
Vector<String> v = new Vector<String>(); v.add("Zonguldak");
v.add("Sinop"); v.add("Trabzon"); v.add("Rize"); v.add("Đzmit"); 
        
 (insetion) v.add(3, "Bafra"); 

 System.out.println("Vektörün uzunluğu :" + v.size()); 
        
 for (int i = 0; i < v.size(); i++) { System.out.println("Vektör öğesi : " + i + " :" +                     v.get(i));
        }
    }
}
