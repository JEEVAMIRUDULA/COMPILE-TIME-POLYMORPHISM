# COMPILE-TIME-POLYMORPHISM
package compile.polymorphisim;

/**
 *
 * @author 1BSCCSA38
 */
public class CompilePolymorphisim {
    public int addition(int x,int y){
        return x+y;
    }
    public int addition (int x,int y,int z){
        return x+y+z;
    }
    public double addition (double x, double y){
        return x+y;
    }
    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        CompilePolymorphisim p= new CompilePolymorphisim ();
        int res1= p.addition(5,15);
        System.out.println("Addition of two integers:"+res1);
        
        int res2=p.addition(10,15,5);
        System.out.println("Addition of three integers:"+res2);
        
        double res3=p.addition(10.15,20.22);
        System.out.println("Addition of two doubles:" + res3);
            
    }
    
}


o/p:

Addition of two integers:20
Addition of three integers:30
Addition of two doubles:30.369999999999997
