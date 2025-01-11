# program-using-class-based-ion-percentage-increase
class PercentageIncrease {
double calculateIncrease(double original, double increase) {
return original + (original * increase / 100);
}
}
public class PercentageIncreaseExample {
public static void main(String[] args) {
PercentageIncrease calc = new PercentageIncrease();
double original = 1000;
double increase = 10;
double result = calc.calculateIncrease(original, increase);
System.out.println(&quot;New value after &quot; + increase + &quot;% increase: &quot; + result);
}
}
Output
New value after 10% increase: 1100.0
