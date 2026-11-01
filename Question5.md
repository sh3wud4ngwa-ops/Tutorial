if (year % 400 == 0 || (year % 4 == 0 && year % 100 != 0))
    System.out.println("Leap year");
else
    System.out.println("Not a leap year");
