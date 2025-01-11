# Student-record-using-access
Public class StudentRecords {
    Public String name;
    String division;
    private int age;

    public StudentRecords(String sname) {
        name = sname;
    }

    public void setDivision(String sdiv) {
        division = sdiv;
    }

    public void setAge(int sage) {
        age = sage;
    }

    Public void printStudent() {
        System.out.println("Student Name: " + name);
        System.out.println("Student Division: " + division);
        System.out.println("Student Age: " + age);
    }

    Public static void main(String[] args) {
       
        StudentRecords student = new StudentRecords("John");
        student.setDivision("A");
        student.setAge(18);

        student.printStudent();
    }
}

OUTPUT:

Student Name: John
Student Division: A
Student Age: 18

