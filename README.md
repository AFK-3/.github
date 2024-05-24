# Diagram

## Context Diagram
![Context Diagram](<DeliverableG1/Context Diagram.JPG>)
## Container Diagram
![Container Diagram](<DeliverableG1/Container Diagram.JPG>)
## Deployment Diagram
![DeploymentDiagram](<DeliverableG1/DeploymentDiagram.JPG>)

## Future Architecture 
![FutureArchitecture](<DeliverableG2/FutureDiagram.png>)

## Risk Storming
![Risk Storming](<DelivarableG3/image.png>)

Dipilih menggunakan pendekatan konsensus dan pada akhirnya disetujui kalau api gateway memiliki kerentanan karena memberikan semua cors untuk lewat dan juga terdapat beberapa servis yang menghardcode link ke api nya pada controller sehingga rawan.
Selain itu, Database yang dimiliki oleh fitur Sell dinilai mengandung terlalu banyak informasi dan sebaiknya dipecah untuk meningkatkan sekuritas karena pada database tersebut mengandung elemen listing, order dan juga user.

## Sell

### Sell Component Diagram
Berikut adalah diagram untuk keseluruhan hubungan komponen sell dan authenticate 
![componentdiagramauthsell](<DelivarableKenichiKomala/componentdiagramauthsell.jpg>)

Berikut adalah diagram untuk komponen pada fitur sell saja
![componentdiagramsell](<DelivarableKenichiKomala/componentdiagramsell.jpg>)

Berikut adalah diagram untuk komponen pada fitur auth saja

![componentdiagramauth](<DelivarableKenichiKomala/componentdiagramauth.jpg>)

### Sell Code diagram
Untuk code diagram auth adalah sebagai berikut 
![codediagramauth](<DelivarableKenichiKomala/codediagramauth.jpg>)

Untuk code diagram sell adalah sebagai berikut 
![codediagramsell](<DelivarableKenichiKomala/codediagramsell.png>)

## Payment

### Payment Code Diagram
![PaymentCodeDiagram](<DeliverableAdrian/PaymentUMLDiagram.png>)

### Payment Component Diagram
![PaymentComponentDiagram](<DeliverableAdrian/PaymentComponentDiagram.png>)

## Buy

### Buy Component Diagram
![Component Diagram - Buy](<DeliverableMAlifAlHakim/ComponentDiagram - Buy.png>)

### Buy Code Diagram
![Code Diagram - Buy](<DeliverableMAlifAlHakim/CodeDiagram - Buy.png>)

## ReviewAndRating

### ReviewAndRating Component Diagram
![Component Diagram - ReviewAndRating](DeliverableFarrellMHanau/ComponentDiagramReview.png)

### ReviewAndRating Code Diagram
![Code Diagram - ReviewAndRating](DeliverableFarrellMHanau/CodeDiagramReview.png)

## Featured Listing

### Featured Listing Component Diagram
![Featured Listing - Component Diagram](<DeliverableRafi/Featured Listing - Component Diagram.png>)

### Featured Listing Code Diagram
![Featured Listing - Code Diagram](<DeliverableRafi/Featured Listing - Code Diagram.png>)

## StaffDashboard

### StaffDashboard Component Diagram
![StaffDashboard - Component Diagram](<DelivarableMHilmyAA/ComponentDiagramStaffDashboard.png>)

### StaffDashboard Code Diagram
![StaffDashboard - Component Diagram](<DelivarableMHilmyAA/CodeDiagramStaffDashboard.png>)
