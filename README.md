# Clases_Ejemplos
Ejemplos de clases con sus metodos

---------

``` ts
( () =>{
    // Ejemplo 1
    class Manager {
        // name: string;
        // id: number;
        // phoneNo: number;
        // location: string;

  constructor(
    public name: string,
    public id: number,
    public phoneNo: number,
    public location: string
  ) {
    this.name = name;
    this.id = id;
    this.phoneNo = phoneNo;
    this.location = location;
  }
  purchaseInventory(): void {}

  recordComplaints(): void {}

  manageStaff(): void {}

  
}

//Ejemplo 2
class Inventory {

  constructor(
    public type: string,
    public status: string
  ) {

    this.type = type;
    this.status = status;
  }
}

//Ejemplo 3
class Guest {

  constructor(
    public name: string,
    public id: number,
    public phoneNo: number,
    public address: string,
    public roomNo: number
  ) {

    this.name = name;
    this.id = id;
    this.phoneNo = phoneNo;
    this.address = address;
    this.roomNo = roomNo;
  }

  checkIn(): void {
  }

  checkOut(): void {
  }

  payBill(): void {
  }

  orderFood(): void {
  }

  submitFeedback(): void {
  }
}

// Ejemplo 4

class Receptionist {
  constructor(
    public name: string,
    public id: number,
    public phoneNo: number,
    public location: string
  ) {
    this.name = name;
    this.id = id;
    this.phoneNo = phoneNo;
    this.location = location;
  }

  checkRoomAvailability(): void {
  }

  bookRoom(): void {
  }

  generateBill(): void {
  }

  acceptCustomerFeedback(): void {
  }
}

// Ejemplo 5
class Rooms {
  constructor(
    public roomNo: number,
    public location: string
  ) {
    this.roomNo =  roomNo;
    this.location = location;
  }
}

//Ejemplo 6
class Bill {
  constructor(
    public billNo: number,
    public guestName: string
  ) {
    this.billNo = billNo;
    this.guestName = guestName;
  }
}

//Ejemplo 7
class Chef {
  constructor(
    public name: string,
    public id: number,
    public location: string
  ) {
    this.name = name;
    this.id = id;
    this.location = location;
  }

  takeOrders(): void {

  }
}

//Ejemplo 8
class FoodItem {
  constructor(
    public id: number,
    public name: string
  ) {
    this.id =  id;
    this.name = name;
  }
}
}) ()
