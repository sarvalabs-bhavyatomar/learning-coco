```bash
coco compile favNum.coco

logiclab init

logiclab start

```

```bash
participant register bhavya

designate bhavya as sender

logic compile favNum from manifest("./favNum.yaml")

# get list of logic
logic

deploy favNum.Init!()

invoke favNum.AddFavNum!(username: "bhavya", favNum: 420)

invoke favNum.GetFavNum(username: "bhavya")
```
