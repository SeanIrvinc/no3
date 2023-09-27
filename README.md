/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 */

package com.mycompany.percabangan;
import java.util.Scanner;
/**
 *
 * @author Lenovo
 */
public class Percabangan {

    public static void main(String[] args) {
      Scanner input= new Scanner (System.in);
      int nilai;
      
      
        System.out.print("Masukan Nilai :  ");
        nilai =  input.nextInt(); 
        
        if (nilai >= 1 && nilai <= 1){
            System.out.println("Senin");
            
        }else if (nilai >= 2 && nilai <= 2){
            System.out.println("Selasa");
        
        }else if (nilai >= 3 && nilai <= 3){
            System.out.println("Rabu");
        
        }else if (nilai >=4 && nilai <= 4){
            System.out.println("Kamis");
        
        }else if (nilai >= 5 && nilai <= 5){
            System.out.println("Jumat");
            
        }else if (nilai >=6 && nilai <=6){
            System.out.println("Sabtu");
            
        }else if (nilai >= 7 && nilai <= 7){
            System.out.println("Minggu");
            
        }
        
       
    }
    
}
