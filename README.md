# sumTwoNum
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package helloworld;

import com.sun.org.apache.xalan.internal.lib.ExsltDynamic;

/**
 *
 * @author M@N@R
 */
public class HelloWorld {

  static int evaluate(String expression) {
    int sum = 0;
    for (String summand: expression.split("\\+"))
      sum += Integer.valueOf(summand);
    return sum;
  }
    public static void main(String[] args) {
        
        int evaluate;
        evaluate = evaluate("4+2");
        System.out.println("The Result "+evaluate);
        
    }
    
}

