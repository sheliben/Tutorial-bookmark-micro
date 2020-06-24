# magic_bookmark

## introduction@fullscreen
בפרויקט זה נכין  קוד לסמניית קסם שעוקבת אחרי הקריאה שלנו

## Step 1 @fullscreen
הכינו שלושה משתנים:
משתנה  כוח מגנטי, משתנה ניקוד קריאה ומשתנה סיכום
השתמשו ב ``||variables: set    ||``  ןהגדירו ערך ראשוני ל-0

```blocks
let magnetic_force = 0
let reading = 0
let total = 0

```
## Step 2
אפסו את המצפן
השתמשו ב: ``||input:calibrateCompass()||``

דוגמה
```blocks
input.calibrateCompass()

```
##step 3
מתחת לאתחול המצפן הוסיפו לבנה שמגדירה ערך כוח מגנטי לפי המצפן 
ובערך אבסולטי של חוזק המגנט
השתמשו ב:
``||Math:abs()||``

##~tutorialhint
רמז
```blocks
magnetic_force = Math.abs(input.magneticForce(Dimension.Strength))
```
## Step 4 
חברו הכל יחד
```blocks

let magnetic_force = 0
let reading = 0
let total = 0
input.calibrateCompass()
magnetic_force = Math.abs(input.magneticForce(Dimension.Strength))

```
## Step 5
הסמנייה שלנו תבדוק כמה זמן אנחנו קוראים לשם כך נשתמש בלולאת חזור תמיד
הכניסו לתוך לולאת החזור 

##Step 6
ראשית, נרצה לדעת מה מצבנו עד לרגע זה
השתמשו בלבנת ``||basic:showNumber()||``
והזינו לתוכה את ערך המשתנה "total"
שיצרתם

## step 7

## Step 8

## Step 9

## Step 10

## Step 13

 @boardname@ הסתכלו בסימולציה  ובדקו מה קורה למשתנים בלחיצה על  כפתור A
## Step 14

 @boardname@ לחצו `|download|` כדי להעביר את הקוד ללוח המיקרו:ביט

