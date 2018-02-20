# classes-ES6-assignment
var Clothes = class {
    constructor(name, size, price){
        this.name = name;
        this.size = size;
        this.price = price;
    }
}
// add code below
class Shirt extends Clothes {
  constructor(){
    super ('kids', 'medium', 15)
  }
}
