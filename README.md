import static
org.junit.jupiter.api.Assertions.as-sertEquals;
import org.junit.jupiter.api.Test;

public class CalculatorTest {
    @Test
    public void testCalculate(){
        CalculatorTest calculator = new CalculatorTest();
        assertEquals(5,calculator.testCalculate("3+2"));
        assertEquals(13,calculator.testCalculate("3+5*2"));
        assertEquals(5,calculator.testCalculate("(4+6)/2"));
        assertEquals(5,calculator.testCalculate("8-8"));
        assertEquals(3.0,calculator.testCalculate("1.5+1.5"));
    }
    
}
