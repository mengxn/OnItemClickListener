###OnItemClickListener
RecyclerView 没有提供列表点击事件，开什么国际玩笑？  
还在Adapter中加点击事情，何必那么麻烦？  
也许你应该看看这里了。
```java
recyclerView.addOnItemTouchListener(new OnItemClickListener() {
    @Override
    public void onItemClick(View view, int position) {
        //do something
    }
});
```
