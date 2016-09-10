# ViewPreparedWaiter
Waiting for a view being visible

# Usage

```java
new ViewPreparedWaiter()
  .waitView(/*The view you want to wait*/, new ViewPreparedWaiter.OnViewPrepared() {
      @Override
      public void onViewPrepared(View viewToWait) {
          //Do something when target view is shown
      }
  });
```
