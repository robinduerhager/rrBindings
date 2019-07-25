# rrBindings


## dev

If you want to develop this project a bit further, make sure that you have this Folder Structure with exactly those files (you have to configure rrBindings/lx64 and rrBindings/win64 manually) which you can get from [RR]/bin/<OS>/
    
```
rrBindings/
    └─── lx64/
    │     └─── lib/
    │          │─── libNodeJs6_RR.node
    │          │─── libQtCore.so.4
    │          │─── librrShared.so.1
    │          └─── package.json
    └─── win64/
    │     │─── msvcp120.dll
    │     │─── msvcr120.dll
    │     │─── nodeJs6_RR.node
    │     │─── package.json
    │     │─── QtCore4.dll
    │     └─── rrShared.dll
    │
    ├─── nodeJS/
    │   ├─── lx64/
    │   │   └───v6/
    │   │       └─── <files...>
    │   │
    │   └─── win64
    │       └───v6
    │           └─── <files...>
    │
    └─── rrExample
       │─── backpack.config.js
       │─── package.json
       │─── tsconfig.json
       └─── src
             └─── index.ts
```

