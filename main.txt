using System;
using System.Collections;
using System.Collections.Generic;


namespace arrayList
{
    class Program
    {
        static void Main(string[] args)
        {
            //System.Collections namespace

            ArrayList liste =new ArrayList();
            liste.Add("Ayşe");
            liste.Add(5);
            liste.Add(true);
            liste.Add('a');

            //içerisindeki verilere erişim
            Console.WriteLine(liste[1]);
            foreach (var item in liste)
            {
                Console.WriteLine(item);
            }

            //AddRange
            Console.WriteLine("*******AddRange******");
            string [] renkler = {"kırmızı","sarı","yeşil"};
            List<int> sayılar = new List<int>(){1,8,3,7,9,92,5};
            liste.AddRange(renkler);
            liste.AddRange(sayılar);

            foreach (var item in liste)
            {
                Console.WriteLine(item);
            }

            //Sort

            //Binary Search--önce sırala sonra ara----kaçıncı indexte olduğunu bulur
            Console.WriteLine("*********binarysearch*******");
            //Consolle.WriteLine(liste.BinarySearch(9));

            //Reverse
            //liste.Reverse();
            // foreach (var item in liste)
                //{
                //  Console.Writeline(item);
                // }


            //Clear
            //liste.Clear();
        






        
        }
    }
}
