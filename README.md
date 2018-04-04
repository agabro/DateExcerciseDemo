public class DateDemo1 {

	public static void main(String[] args) {
	
	
	Date1 date1 = new Date1();
	System.out.println(date1);
	
	Date1 date2 = new Date1(22, 12, 2018);
	System.out.println(date2);
	
	Date1 date3 = new Date1(23, 3, 2018);
	System.out.println(date3);
	
	Date1 date4 = new Date1(date2);
	System.out.println(date4);
	
	date3.incDay(70);
	System.out.println(date3);
	
	date2.decDay(15);
	System.out.println(date2);
	
	}
}
