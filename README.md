# AnotherJavaDay
So, i was studying printf output and i was like "oh this is easy", %s for String and %c for character AND THEN I PROCEED TO TYPE %i for "int" since OBVIOUSLY why wouldn't it be the correct thing to do, right? and then i spent half of an hour trying to understand until i have up and googled why the fuck i was getting errors, WHAT A SURPRISE THAT A %i IS NOT FOR int and THE CORRECT COMMAND IS "%d' AND ANOTHER FUN FACT THE PRINTF OUTPUT FOR double IS "%f". I have no words.

    public static void main(String[] args) {

        String name = "Seiya";
        char firstLetter = 'S';
        int age = 20;
        double height = 1.83;
        boolean isSaint = true;

        System.out.printf("Hello %s\n" , name);
        System.out.printf("Your name starts with %c\n" , firstLetter);
        System.out.printf("You're %d years old\n" , age);
        System.out.printf("You're %.2f cm tall\n" , height);
        System.out.printf("Saint: %b\n" , isSaint);


    }
