# AI-Job-Market-Analysis-Dashboard-
The AI Job Market Analysis Dashboard analyzes AI employment trends, including job roles, salaries, experience levels, locations, companies, and remote opportunities. Interactive charts and KPIs make the data easy to understand, helping students, job seekers, recruiters, and organizations make informed career and hiring decisions.
// // class Music{
// //     void print(){
// //         System.out.println("Music playing....");
// //     }

// // }

// // class Main{
// //     public static void main(String[] args) {
// //         Music m = new Music();
// //     void print(){
// //         System.out.println("Music playing....");
// //     }
// // }

// interface A{
//     void show();
// }

// class Main{
//     public static void main(String[] args) {
//         A obj = new A(){
//             public void show(){
//                 System.out.println("Im from interface A");
//             }
//         };
//         obj.show();
//         A obj1 = () -> System.out.println("I M object2");
//         obj1.show();
//     }
// }
// interface Walkable{
//    int walk(int steps) {
// }

// class Main{
//     public static void main(String[] args) {
//         Walkable w = (steps) -> 2 * steps;
//         System.out.println(w.walk(4));

//         walkable w1 = new walkable(){
//             public int walk(int steps){
//                 return 2 * steps;
//             }
//         };
//     System.out.println(w1.walk(2));
//     }
// }

import java.io.*;

public class  {
    public static void main(String[] args) {
        try {
            FileReader fr = new FileReader("studend.txt");

            int i;
            while ((i = fr.read()) !=-1){
                System.out.println((char)i);
            }

            fr.close();
        } catch (Exception e) {


            System.out.println(e);
            out.println("File not found");
        }
    }
}

class abc{
     public static void main(String[] args ){
        Thread t1 = new Thread(() -> {
            for (int i = 0; i < 5; i++) {
                System.out.println("Thread 1: " + i);
            }
        });
    }
}

class Bank{
    int balance = 1000;
    synchronized void withdraw(int amount){
        if (balance >= amount){
            System.out.println("processing....");
        balance = balance - amount; 
            System.out.println("I");
        }
    }
}

//there are a file called student.txt in the same directory as this java file.
//The program reads the contents of the file and prints it to the console.
//If the file is not found, it catches the exception and prints an error message.
//please make sure to create a file named "student.txt" in the same directory as this Java
//  file and add some content to it before running the program
class FileReadExample{
    public static void main(String[] args) {
        try {
            FileReader fr = new FileReader("student.txt");

            int i;
            while ((i = fr.read()) !=-1){
                System.out.print((char)i);
            }
            fr.close();
        } catch (Exception e) {
            System.out.println(e);
            System.out.println("File not found");
        }
    }
}

public void main(String[] args) {
        for (int i = 0; i < 5; i++) {
            t.data = i;
            t.hasData = true;
            System.out.println("Produced: " + i);
            class producer extends Thread{
                public void run(){
                    }
                }
        }
    class consumer extends Thread{
        public void run(){
            for(int i = 1; i <= 5; i++){
                if (t.hasData){
                    System.out.println("Consumed: " + t.data);
                    t.hasData = false;
                }
            }
        }
class abc{
    public static void main(String[] args) {
        Thread t1 = new Table();
        producer p = new producer();
        consumer c = new consumer();
        p.start();
        c.start();
    }
}
