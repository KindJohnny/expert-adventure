HEAD -- это голова.
Коммит -- это всему голова.
Статусы файлов:

```mermaid
graph LR;
untracked -- "git add"     --> staged;
staged    -- "git commit"  --> tracked/committed 
%%комментарий
```


```mermaid
  graph TD;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```

