import java.util.HashMap;
import java.util.Map.Entry;

public class Main
{
	public static void main(String[] args)
	{
		HashMap <Integer, Integer> inputHashMap = new HashMap<>();
		HashMap <Integer, String> OutputHashMapfinal = new HashMap<>();
		
		
		inputHashMap.put(1,80);
		inputHashMap.put(3,90);
		inputHashMap.put(2,75);
		inputHashMap.put(5,59);
		
		
		
		class Calculation
		{
		    HashMap <Integer, String> outputHashMap = new HashMap<>();
		    public HashMap<Integer,String> outputfuntion(HashMap<Integer,Integer> in)
		    {
		        for(Entry<Integer,Integer> i : in.entrySet())
		        {
		            if(i.getValue()>=90)
		            {
		                outputHashMap.put(i.getKey(),"Gold");
		            }
		            else if(i.getValue()>=80)
		            {
		                outputHashMap.put(i.getKey(),"Silver");
		            }
		            else if(i.getValue()>=70)
		            {
		                outputHashMap.put(i.getKey(),"Bronze");
		            }
		        }
		        return outputHashMap;
		    }
		}
		Calculation c = new Calculation();
		OutputHashMapfinal = c.outputfuntion(inputHashMap);
		System.out.println(OutputHashMapfinal);
		
	}
}
