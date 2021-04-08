# DiagramaClases

classDiagram
    ReadingItem <|-- Encyclopedia
    ReadingItem <|-- Magazine
    ReadingItem <|-- Book
    GST_Chargeable <|.. Encyclopedia
    GST_Chargeable <|.. Magazine
    ReadingItem "1" <-- "0..*"Customer : buy
    
    class ReadingItem{
        <<abstract>>
      -title : String
      -price : double
      +ReadingItem(double, String)
      +getName() String
      +getPrice() double
      +calculatePrice()* double
      +displayInfo()* void
    }
    class GST_Chargeable{
    <<interface>>
    -RATE : double = 0.06 [readOnly]
    +getGSTCharges() double
    }
    class Encyclopedia{
      -year : int
      +Encyclopedia(String, double, int)
    }
    class Magazine{
      -monthIssue : int
      -year : int
      +Magazine(int, int, double, String)
    }
    class Book{
      -author : String
      -year : int
      +Book(String, double, String, int)
    }
    class Customer{
    -customerName : String
    -totalPay : double
    +buy(ReadingItem) void
    +getTotalPay() double
    +toString String
    }   
