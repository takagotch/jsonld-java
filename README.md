### jsonld-java
---
https://github.com/jsonld-java/jsonld-java

```java
InputStream inputStream = new FileInputStream("input.json");
Object jsonObject = JsonUtils.fromInputStream(inputStream);
Map conetxt = new HashMap();
JsonLdOptions options = new JsondOptions();
Object compact = JsondProcessor.compat(jsonObject, context, options);
System.out.print(JsonUtils.toPrettyString(compact));

```

```
```

```
```


