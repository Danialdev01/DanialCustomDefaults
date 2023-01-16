# EasySassTemplate

It's just a bad version of tailwind but with sass files.

## Installation :

(if you are using src/assets/ folder structure)
```
cd src/ 
```
or
```
mkdir src/
cd src/
```
install the packages
```
git clone https://github.com/Danialdev01/EasySassTemplate assets/
```

## Usage :

#### Vscode :

Open command palet or press Ctrl + Shift + p

Type `ext install sass-indented` in the command palet

Install the extention and press watch sass

(Try to only add/edit in /scss/Custom)
base and Animation folder are just the defaults but feel free to edit if you see fit.

#### Terminal :

(make sure you have install sass)

```
cd ~ | npm install -g sass
```

then run 

```
sass --watch scss/main.scss src/css/main.css
```

## Sass Styling
- [Class](#class)
- [Colors](#colors)
- [Shapes](#shapes)

### Class
#### Spacing
| ClassName         | range | Atribut               |
|-------------------|-------|-----------------------|
| .main-container   | none  | padding left right    |
| .fit              | none  | fit-content           |
| .w                | 1-10  | width %               |
| .max-w            | 1-10  | max-width             |
| .p                | 1-10  | padding right-left 10+|
| .p-r              | 1-10  | padding right 10+     |
| .p-l              | 1-10  | padding left 10+      |

#### Flexbox
| ClassName         | range |    Atribut            |
|-------------------|-------|-----------------------|
| .flex             | none  | display-flex          |
| .flex-jc-sb       | 1-10  | justify space-between |
| .flex-jc-c        | 1-10  | justify center        |
| .flex-ai-c        | 1-10  | align-items center    |

### Colors
- [Normal Default Colors](#font-color-normal)
- [Background Colors](#background-color-normal)
- [Spesific colors]()
#### Font color normal
| ClassName         | range |    Atribut            |
|-------------------|-------|-----------------------|
| .red              | none  | color:red             |
| .blue             | none  | color:blue            |
| .black            | none  | color:black           |
| .white            | none  | color:white           |
| .orange           | none  | color:orange          |
| .green            | none  | color:green           |
| .gray             | none  | color:gray            |
| .yellow           | none  | color:yellow          |
| .cyan             | none  | color:cyan            |

#### Background color normal
| ClassName         | range |    Atribut              |
|-------------------|-------|-------------------------|
| .bg-red           | none  | background-color:red    |
| .bg-blue          | none  | background-color:blue   |
| .bg-black         | none  | background-color:black  |
| .bg-white         | none  | background-color:white  | 
| .bg-orange        | none  | background-color:orange |
| .bg-green         | none  | background-color:green  |
| .bg-gray          | none  | background-color:gray   |
| .bg-yellow        | none  | background-color:yellow |
| .bg-cyan          | none  | background-color:cyan   |

### Shapes
#### Box
| ClassName         | range |    Atribut              |
|-------------------|-------|-------------------------|
| .box              | none  | normal box css          |
| .box-transparent  | none  | transparent box         |
| .boxx             | 1-10  | box with border size x |

#### Circle
| ClassName         | range |    Atribut              |
|-------------------|-------|-------------------------|
| .circle           | none  | normal circle css       |
