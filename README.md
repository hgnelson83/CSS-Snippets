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

# Navigation 
## Using Flex
```
nav ul {
  display: flex;
  justify-content: space-between;
}
```
### Html
```
<nav>
  <ul>
    <li><a href="#">Link 1</a></li>
    <li><a href="#">Link 2</a></li>
    <li><a href="#">Link 3</a></li>
    <li><a href="#">Link 4</a></li>
  </ul>
</nav>
```
