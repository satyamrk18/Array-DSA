# Array-DSA
All the array code for DSA
// Integer array

//fun main()
// {
//     val arr= arrayOf<Int>(1,2,3,4,5,)
//     for(i in arr)
//     println(i)
//     println(arr[0])
//     println(arr.size)
//     if( 2 in arr)
//     {
//         println("exist")
//     }
//     for(arr in 2..4)
//     println(arr)
//     for (arr in 1..5)
//     if(arr==5)
//     {
//         break
        
//     }
//     println(arr)
// }
//fun main()
//{
    //val R1= arrayOf<Int>(1,2,4,5,6,7,8,9,10)when we want to skip any perticular charater
//     for(i in 1..10)
//     //print(i)
//     {
//         if(i==5)
//     {
//         continue
//     }
//     println(i)
// }
// for(i in R1){
//     //println(i)
//     //println(R1.size)
//     // println(R1.max())
//     // println(R1.min())
//     //if(i%2!=0)//1,3,5,7,9
//     if(i%2==0)//2,,4,6,8,10
//     {
//        // println(i)
//        println(i)
//     }
    //println(i)
//}
// for (i in R1.reversed())//reversed arrya
// {
//   println(i)
// }
// fun main()
// {
//     val R1= arrayOf<Int>(1,2,4,5,6,7,8,9,10)
// for(i in R1){
//     //println(i)
// }
// println(R1.max())
// var max=10
// println(R1.min())
// if(R1.max()==R1[8]){println("true")}
// else println("false")
// val n=10
// var sum = 1
// for(i in 1..10){
//      sum+=i
     
// }
// println("expected sum is:$sum")
// val expectedsum=55
// println(R1.sum())
// val actualsum=52
// println("actual sum is: $actualsum") // find missing element in 1 to 10
// val missing_value= expectedsum-actualsum
// println("missing value in between 1 to 10 is=$missing_value")
//}

// fun main()
// {
//      val Num = arrayOf<Int>(1,2,3,4,5,6,7,8,9,10)  // second largest number                                                                      
//      var element=(Num.max())
//     println("before the sorting maximum element is=$element")
    
//     for(i in Num)
//     {
//        if(i==element)
//        { 
//          continue
//        } 
//         //println(i)
//         val copyArray = arrayOf(i)
//         val result=copyArray.max()
     
//     }  
// }
// fun main()
// {
//     val S=arrayOf<Int>(6,4,9,10,3,6,2,6,)
//     val sorted=S.sorted()
//     println(sorted)//sequence of array
//     val M=sorted.max()
//     println("max element is:$M")
// }
   
// fun main()
// {
//     val S=arrayOf<Int>(1,-2,3,4,-5,6,8,-9,10)
//     for(i in S)
//     {
//        // println(i)
//         if(i <0)
//         {
//         continue//if we want to println only +ve or -ve value   
//         }
//         println(i)
//         // else
//         // {
//         //     println("the value is +v $i")
//         // }

//     }
// }

//String array

// fun main()
// {
//     val S=arrayOf<String>("apple","banana","cherry","date","elderberry") 
//     for(i in S)
    {
        //println(i)
        // if(i==="apple")
        // {
        //     continue
        // }
        //println(i.reversed()) // when we want to reverse the word in array
        }
        //println(S[0])
        //println(S.reversed())//when we want to revesed the array
        //println(S.sorted()) //when we want to order alphabatically

//}
// //arrays:- object that stores multiple values of same type
// // arrays has fixed size,length is fixed
// //syntax var arr = arrayOf("satyam","shivam","pratik")
// //indexing starts with 0
// //0th index = satyam
// //1st index = shivam
// //2nd index = pratik
// fun main()
// {
//     var arr = arrayOf(1,2,3,4,5,)//implicit array
//     var arr1 = arrayOf("satyam","shivam","pratik")//implicit aaray
//     var arr2 = arrayOf<Int>(1,2,3,4,5,6,)//explicit array
// //    for( i in arr)
// //        println(i)
// //    for (i in arr1)
// //        println(i)
// //    for ( i in arr2)
// //        println(i)
// //    for((i,e)in arr.withIndex())//to print with index
// //    {
// //        println("$i-$e")
// //    }
// //    println(arr[0])// to access particuler element the index is given
// //    arr.set(1,8)//to modify the array value
// //    println(arr[1])
//    // println(arr.size)//to determine the size of array
// for ( i in arr)
//     println(i)
//     for ( (i,e)in arr.withIndex())
//         println("$i-$e")
//  }
// fun main() {
//     val R1 = arrayOf(1, 2, 3, 4, 5, 6, 7, 8, 9)
    
//     println("Original array:")
//     for (i in R1) {
//         println(i)
//     }
    
//     println("Array after adding each index with itself:")
//     for (i in R1.indices) {
//         R1[i] = R1[i] + R1[i]
//         println(R1[i])
//     }
// }


