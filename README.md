```java
public class MyIdentity {
    public static void main(String[] args) {
        // 我的身份？不用选，全都要！
        int choice = 3; 

        switch (choice) {
            case 1:
                System.out.println("🤵 Tech-minded PM: 懂代码的产品经理，不画空中楼阁～");
                break;
            case 2:
                System.out.println("👨💻 Product-minded dev: 懂产品的程序员，不写无用代码～");
                break;
            case 3:
                System.out.println("🔥 Why choose? Tech-minded PM + Product-minded dev — I want it all!");
                break;
            default:
                System.out.println("😜 别纠结，反正我全都要～");
                break;
        }
    }
}
