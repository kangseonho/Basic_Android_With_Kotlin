### 📗 Principle
```
1. Separation of concerns(soc): UI 기반 클래스(Activity or Fragment)에는 UI, OS와 상호작용하는 Logic만을 포함해야 한다.
2. Data Model에서만 UI에 영향을 주어야 한다.
```

### 🔄 LifeCycle
```

```

### 📖 Context
```
특정 Activity의 객체의 Context를 넘겨줄 때에는 해당 객체의 Context만 넘겨준다.
Activity나 서비스 이외에 싱글톤 객체에서 넘겨줄 때에는 getApplicationContext를 사용한다.

-> Activity는 가비지 콜렉터에 수집되지 않는다. 따라서 싱글톤 객체를 넘겨줄 때 Activity의
   Context를 넘겨준다면 메모리 누수가 발생할 수 있다.
```


#### referenced by

<https://developer.android.com/docs?hl=ko>
