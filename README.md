# Diagramas de clases
Ejercicios de diagramas de clases realizadas con [Mermaid live editor](https://mermaid-js.github.io/mermaid-live-editor)  
### 1. Lectura
Imagen realizada con el editor:
[![](https://mermaid.ink/img/eyJjb2RlIjoiY2xhc3NEaWFncmFtXG4gICAgUmVhZGluZ0l0ZW0gPHwtLSBFbmN5Y2xvcGVkaWFcbiAgICBSZWFkaW5nSXRlbSA8fC0tIE1hZ2F6aW5lXG4gICAgUmVhZGluZ0l0ZW0gPHwtLSBCb29rXG4gICAgR1NUX0NoYXJnZWFibGUgPHwuLiBFbmN5Y2xvcGVkaWFcbiAgICBHU1RfQ2hhcmdlYWJsZSA8fC4uIE1hZ2F6aW5lXG4gICAgUmVhZGluZ0l0ZW0gXCIxXCIgPC0tIFwiMC4uKlwiQ3VzdG9tZXIgOiBidXlcbiAgICBcbiAgICBjbGFzcyBSZWFkaW5nSXRlbXtcbiAgICAgICAgPDxhYnN0cmFjdD4-XG4gICAgICAtdGl0bGUgOiBTdHJpbmdcbiAgICAgIC1wcmljZSA6IGRvdWJsZVxuICAgICAgK1JlYWRpbmdJdGVtKGRvdWJsZSwgU3RyaW5nKVxuICAgICAgK2dldE5hbWUoKSBTdHJpbmdcbiAgICAgICtnZXRQcmljZSgpIGRvdWJsZVxuICAgICAgK2NhbGN1bGF0ZVByaWNlKCkqIGRvdWJsZVxuICAgICAgK2Rpc3BsYXlJbmZvKCkqIHZvaWRcbiAgICB9XG4gICAgY2xhc3MgR1NUX0NoYXJnZWFibGV7XG4gICAgPDxpbnRlcmZhY2U-PlxuICAgIC1SQVRFIDogZG91YmxlID0gMC4wNiBbcmVhZE9ubHldXG4gICAgK2dldEdTVENoYXJnZXMoKSBkb3VibGVcbiAgICB9XG4gICAgY2xhc3MgRW5jeWNsb3BlZGlhe1xuICAgICAgLXllYXIgOiBpbnRcbiAgICAgICtFbmN5Y2xvcGVkaWEoU3RyaW5nLCBkb3VibGUsIGludClcbiAgICB9XG4gICAgY2xhc3MgTWFnYXppbmV7XG4gICAgICAtbW9udGhJc3N1ZSA6IGludFxuICAgICAgLXllYXIgOiBpbnRcbiAgICAgICtNYWdhemluZShpbnQsIGludCwgZG91YmxlLCBTdHJpbmcpXG4gICAgfVxuICAgIGNsYXNzIEJvb2t7XG4gICAgICAtYXV0aG9yIDogU3RyaW5nXG4gICAgICAteWVhciA6IGludFxuICAgICAgK0Jvb2soU3RyaW5nLCBkb3VibGUsIFN0cmluZywgaW50KVxuICAgIH1cbiAgICBjbGFzcyBDdXN0b21lcntcbiAgICAtY3VzdG9tZXJOYW1lIDogU3RyaW5nXG4gICAgLXRvdGFsUGF5IDogZG91YmxlXG4gICAgK2J1eShSZWFkaW5nSXRlbSkgdm9pZFxuICAgICtnZXRUb3RhbFBheSgpIGRvdWJsZVxuICAgICt0b1N0cmluZyBTdHJpbmdcbiAgICB9ICAgIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjpmYWxzZX0)](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiY2xhc3NEaWFncmFtXG4gICAgUmVhZGluZ0l0ZW0gPHwtLSBFbmN5Y2xvcGVkaWFcbiAgICBSZWFkaW5nSXRlbSA8fC0tIE1hZ2F6aW5lXG4gICAgUmVhZGluZ0l0ZW0gPHwtLSBCb29rXG4gICAgR1NUX0NoYXJnZWFibGUgPHwuLiBFbmN5Y2xvcGVkaWFcbiAgICBHU1RfQ2hhcmdlYWJsZSA8fC4uIE1hZ2F6aW5lXG4gICAgUmVhZGluZ0l0ZW0gXCIxXCIgPC0tIFwiMC4uKlwiQ3VzdG9tZXIgOiBidXlcbiAgICBcbiAgICBjbGFzcyBSZWFkaW5nSXRlbXtcbiAgICAgICAgPDxhYnN0cmFjdD4-XG4gICAgICAtdGl0bGUgOiBTdHJpbmdcbiAgICAgIC1wcmljZSA6IGRvdWJsZVxuICAgICAgK1JlYWRpbmdJdGVtKGRvdWJsZSwgU3RyaW5nKVxuICAgICAgK2dldE5hbWUoKSBTdHJpbmdcbiAgICAgICtnZXRQcmljZSgpIGRvdWJsZVxuICAgICAgK2NhbGN1bGF0ZVByaWNlKCkqIGRvdWJsZVxuICAgICAgK2Rpc3BsYXlJbmZvKCkqIHZvaWRcbiAgICB9XG4gICAgY2xhc3MgR1NUX0NoYXJnZWFibGV7XG4gICAgPDxpbnRlcmZhY2U-PlxuICAgIC1SQVRFIDogZG91YmxlID0gMC4wNiBbcmVhZE9ubHldXG4gICAgK2dldEdTVENoYXJnZXMoKSBkb3VibGVcbiAgICB9XG4gICAgY2xhc3MgRW5jeWNsb3BlZGlhe1xuICAgICAgLXllYXIgOiBpbnRcbiAgICAgICtFbmN5Y2xvcGVkaWEoU3RyaW5nLCBkb3VibGUsIGludClcbiAgICB9XG4gICAgY2xhc3MgTWFnYXppbmV7XG4gICAgICAtbW9udGhJc3N1ZSA6IGludFxuICAgICAgLXllYXIgOiBpbnRcbiAgICAgICtNYWdhemluZShpbnQsIGludCwgZG91YmxlLCBTdHJpbmcpXG4gICAgfVxuICAgIGNsYXNzIEJvb2t7XG4gICAgICAtYXV0aG9yIDogU3RyaW5nXG4gICAgICAteWVhciA6IGludFxuICAgICAgK0Jvb2soU3RyaW5nLCBkb3VibGUsIFN0cmluZywgaW50KVxuICAgIH1cbiAgICBjbGFzcyBDdXN0b21lcntcbiAgICAtY3VzdG9tZXJOYW1lIDogU3RyaW5nXG4gICAgLXRvdGFsUGF5IDogZG91YmxlXG4gICAgK2J1eShSZWFkaW5nSXRlbSkgdm9pZFxuICAgICtnZXRUb3RhbFBheSgpIGRvdWJsZVxuICAgICt0b1N0cmluZyBTdHJpbmdcbiAgICB9ICAgIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjpmYWxzZX0)  

Código con el que se ha realizado la imagen:
~~~
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
~~~
    
### 2. Pet
Imagen realizada con el editor:  

[![](https://mermaid.ink/img/eyJjb2RlIjoiY2xhc3NEaWFncmFtXG4gICAgQW5pbWFsIDx8LS0gQ2F0XG4gICAgQW5pbWFsIDx8LS0gU3BpZGVyXG4gICAgQW5pbWFsIDx8LS0gRmlzaFxuICAgIFBldCA8fC4uIEZpc2hcbiAgICBQZXQgPHwuLiBDYXRcbiAgICBcbiAgICBjbGFzcyBBbmltYWx7XG4gICAgICAgIDw8YWJzdHJhY3Q-PlxuICAgICAgI2xlZ3MgOiBpbnRcbiAgICAgICNBbmltYWwoaW50KVxuICAgICAgK3dhbGsoKSB2b2lkXG4gICAgICArZWF0KCkgdm9pZFxuICAgIH1cbiAgICBjbGFzcyBQZXR7XG4gICAgPDxpbnRlcmZhY2U-PlxuICAgICtnZXROYW1lKCkgU3RyaW5nXG4gICAgK3NldE5hbWUoU3RyaW5nKSB2b2lkXG4gICAgK3BsYXkoKVxuICAgIH1cbiAgICBjbGFzcyBTcGlkZXJ7XG4gICAgICArU3BpZGVyKClcbiAgICAgICtlYXQoKSB2b2lkXG4gICAgfVxuICAgIGNsYXNzIENhdHtcbiAgICAgIC1uYW1lIDogU3RyaW5nXG4gICAgICArQ2F0KClcbiAgICAgICtDYXQoU3RyaW5nKVxuICAgICAgK2VhdCgpIHZvaWRcbiAgICB9XG4gICAgY2xhc3MgRmlzaHtcbiAgICAgIC1uYW1lIDogU3RyaW5nXG4gICAgICArRmlzaCgpXG4gICAgICArRmlzaChTdHJpbmcpXG4gICAgICArd2FsaygpIHZvaWRcbiAgICAgICtlYXQoKSB2b2lkXG4gICAgfSIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6ZmFsc2V9)](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiY2xhc3NEaWFncmFtXG4gICAgQW5pbWFsIDx8LS0gQ2F0XG4gICAgQW5pbWFsIDx8LS0gU3BpZGVyXG4gICAgQW5pbWFsIDx8LS0gRmlzaFxuICAgIFBldCA8fC4uIEZpc2hcbiAgICBQZXQgPHwuLiBDYXRcbiAgICBcbiAgICBjbGFzcyBBbmltYWx7XG4gICAgICAgIDw8YWJzdHJhY3Q-PlxuICAgICAgI2xlZ3MgOiBpbnRcbiAgICAgICNBbmltYWwoaW50KVxuICAgICAgK3dhbGsoKSB2b2lkXG4gICAgICArZWF0KCkgdm9pZFxuICAgIH1cbiAgICBjbGFzcyBQZXR7XG4gICAgPDxpbnRlcmZhY2U-PlxuICAgICtnZXROYW1lKCkgU3RyaW5nXG4gICAgK3NldE5hbWUoU3RyaW5nKSB2b2lkXG4gICAgK3BsYXkoKVxuICAgIH1cbiAgICBjbGFzcyBTcGlkZXJ7XG4gICAgICArU3BpZGVyKClcbiAgICAgICtlYXQoKSB2b2lkXG4gICAgfVxuICAgIGNsYXNzIENhdHtcbiAgICAgIC1uYW1lIDogU3RyaW5nXG4gICAgICArQ2F0KClcbiAgICAgICtDYXQoU3RyaW5nKVxuICAgICAgK2VhdCgpIHZvaWRcbiAgICB9XG4gICAgY2xhc3MgRmlzaHtcbiAgICAgIC1uYW1lIDogU3RyaW5nXG4gICAgICArRmlzaCgpXG4gICAgICArRmlzaChTdHJpbmcpXG4gICAgICArd2FsaygpIHZvaWRcbiAgICAgICtlYXQoKSB2b2lkXG4gICAgfSIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In0sInVwZGF0ZUVkaXRvciI6ZmFsc2V9)  

Código con el que se ha realizado la imagen:
~~~
    Animal <|-- Cat
    Animal <|-- Spider
    Animal <|-- Fish
    Pet <|.. Fish
    Pet <|.. Cat
    
    class Animal{
        <<abstract>>
      #legs : int
      #Animal(int)
      +walk() void
      +eat() void
    }
    class Pet{
    <<interface>>
    +getName() String
    +setName(String) void
    +play()
    }
    class Spider{
      +Spider()
      +eat() void
    }
    class Cat{
      -name : String
      +Cat()
      +Cat(String)
      +eat() void
    }
    class Fish{
      -name : String
      +Fish()
      +Fish(String)
      +walk() void
      +eat() void
    }
~~~    
