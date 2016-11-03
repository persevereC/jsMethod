###1.冒泡排序
* 从第一个元素开始比较，遇到比自己小的就交换位置；
* 交换次数最多，性能最差。
* function bubble(arr){
      var len=arr.length;
      for(var i=0;i<len;i++){
          for(var j=0;j<len-1-i;j++){
              if(arr[j]>arr[j+1]){
                  var tmp=arr[j+1];
                  arr[j+1]=arr[i];
                  arr[j]=tmp;
              }
          }
      }
      return arr;
  }
  
###2.插入排序
###3.希尔排序
###4.归并排序
###5.快速排序
###6.选择排序
###7.奇偶排序
