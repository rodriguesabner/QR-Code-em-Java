# QR Code with Webcam - Java

Leia QR Code utilizando a sua Webcam.

## Getting Started

Understand how code deployment works. (The project reads QR Code and Barcode).

Tutorial: https://www.youtube.com/watch?v=9CDaUrjKBIA

### Prerequisites

```
Java 1.8 >
Netbeans 8.2
Webcam
Willpower
```

### Time to code

A step by step series of examples that tell you how to get a development env running

Tell your software what quality you want your webcam to have.

```
Dimension size = WebcamResolution.QVGA.getSize();
Obs: Webcam quality ranges from 4K to QVGA
```

Choose which camera you want to use

```
webcam = Webcam.getWebcams().get(0); //0 is default webcam
```

And show the result your webcam got

```
result_field.setText(result.getText());
```

You can get examples by downloading the project.

## Libs

* Libraries are included in the project.

## Authors

* **Abner Rodrigues** - *Initial work* - [KingAspx](https://github.com/kingaspx)

## Screenshots

![Screenshot_2](https://user-images.githubusercontent.com/40338524/58518645-526d3400-8186-11e9-829d-8870dc1bfd02.png)

![Screenshot_3](https://user-images.githubusercontent.com/40338524/58518669-6add4e80-8186-11e9-8e14-9098db85c588.png)
