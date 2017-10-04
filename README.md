# LESS

## Docs

## Installation
- Install NPM `$ brew install npm`
- Install less via NPMs `$ npm install -g less`
- Make sure that lessc is installed - `$ lessc`

## Getting started 
- See `style.less` for a simple definition.
```
@base: #f938ab;
@size: 10px;

.test-style{
        color: @base;
        font-size: @size;
}
```
- Run `lessc styles.less styles.css`
```
.test-style {
  color: #f938ab;
  font-size: 10px;
}
```



