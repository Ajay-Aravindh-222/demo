package com.firstproject;

import java.util.Arrays;

public class MainClass {
    public static void main(String[] args) {
        int numbers[] = new int[5];
        numbers[0] = 5;
        numbers[1] = 15;
        numbers[2] = 25;
        numbers[3] = 35;
        int len = numbers.length;
        char name[] = {'a', 'b', 'c'};
        int name_len = name.length;
        char name1[] = name.clone();
        System.out.println(name);
        System.out.println(name1);
        System.out.println(name_len);
        System.out.println(Arrays.toString(numbers));
        System.out.println(len);
    }
}
