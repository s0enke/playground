![Alt text](https://g.gravizo.com/source/custom_mark2?https%3A%2F%2Fraw.githubusercontent.com%2Fs0enke%2Fplayground%2Fmaster%2FREADME.md)

<details> 
<summary></summary>
custom_mark10
  digraph G {
    aize ="4,4";
    main [shape=box];
    main -> parse [weight=8];
    parse -> execute;
    main -> init [style=dotted];
    main -> cleanup;
    execute -> { make_string; printf};
    init -> make_string;
    edge [color=red];
    main -> printf [style=bold,label="100 times"];
    make_string [label="make a string"];
    node [shape=box,style=filled,color=".7 .3 1.0"];
    execute -> compare;
  }
custom_mark2
</details>
