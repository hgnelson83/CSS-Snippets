# Centering 
## Using Flex
```
.parent {
  display: flex;
  justify-content: center;
  align-items: center;
}
```
## Using Grid
```
.parent {
  display: grid;
  place-content: center;
}
```
## Using Position
```
.parent {
  position: relative;
}

.child {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
```
## Using Grid & Margin
```
.parent {
  display: grid;
}

.child {
  margin: auto;
}
```
## Using Flex & Margin
```
.parent {
  display: flex;
}

.child {
  margin: auto;
}
```
