# DWDM21
Data Warehouse &amp; Data Mining 2021

เกียรติศักดิ์ แสนจันทร์ 623021041-7

Name Group : SAKUNA

Kiartisak Senchan 623021041-7 (ME)

Ratima Chinwong 623020042-0

Jennapa Phunanil 623020515-3

Suphalaksana Buajan 623020540-4

Watcharaporn Nammungkhun 623020535-7

# สรุปบทเรียน 
  **ʕ￫ᴥ￩　ʔ** 
## ภาคทฤษฎี    
**Ⅰ.Chapter 1 Introduction** [คลิกที่นี่](https://github.com/team0243/DWDM21)

   * Data Mining คืออะไร?

   * Data Warehouse คืออะไร?

   * ตัวอย่างข้อมูล



**Ⅱ.Chapter 2 Getting to Know Your Data** [คลิกที่นี่](https://github.com/team0243/DWDM21/blob/main/Chapter2.pdf)


   * ขนาดของข้อมูล,ชนิดของข้อมูล,คุณสมบัติต่างๆ

**Ⅲ  Chapter 3 Data Preprocessing**
[คลิกที่นี่](https://github.com/team0243/DWDM21/blob/main/Chapter3.pdf)


  * Data Cleaning คืออะไร? หน้าที่?

  * Data Integration คืออะไร? หน้าที่?

  * Data Reduction and Tranformation คืออะไร? หน้าที่?

  * Dimensionality Reduction คืออะไร?

**Ⅳ Chapter 6 Mining Frequent Patterns, Association and Correlations:Basic Concepts and Methods**
[คลิกที่นี่](https://github.com/team0243/DWDM21/blob/main/Chapter6.pdf)

  * Patterns คืออะไร?

  * ตัวอย่างการนำ patterns ไปใช้ประโยชน์

  * การนำ K-itemsets มาใช้/การคำนวณหาค่า K-itemsets

  * Frequent Itemsets(Patterns)

**Ⅴ. Chapter 8 Classification:Basic Concepts**
[คลิกที่นี่](https://github.com/team0243/DWDM21/blob/main/Chapter7_Classification_Lecture.pdf)


   
  * พื้นฐาน Classification
    
  * Decision Tree Induction
    
  * Model Evalution And Selection 
    
  * summary
 
 
**Ⅵ. Chapter 8+9 Neural Network for Classification**
[คลิกที่นี่](https://github.com/team0243/DWDM21/blob/main/Chap7-8%20Neural%20Network%20%26%20Confusion%20Matrix.pdf)

   * องค์ประกอบของ Perceptron

   * ตัวอย่าง และผลการเรียนฟังก์ชัน AND & XOR ด้วยกฏ Perceptron

   * การหาค่า Procision/Recall + Test data เพิ่มเติม

**Ⅶ. Chapter 10 Cluster Analysis:Basic Concepts and Methods**
[คลิกที่นี่](https://github.com/team0243/DWDM21/blob/main/Chapter10.pdf)

  * K-Means คืออะไร?

  * ตัวอย่างการหาค่า K-Means

  * การทำ Clustering แบบลำดับชั้น

 * วิธีการวัดแบ่งออกเป็น External & Internal

  * การทำ Cluster ที่ดีต้องมี 4 ข้อ อะไรบ้าง?

 * ในกรณีที่เราไม่รู้แนวคำตอบสามารถทำอย่างไรได้บ้าง?

## ภาคปฏิบัติ (Google Colab)

**บทที่ 2 Getting to Know Your Data**

  *  [Basic Python](https://github.com/team0243/DWDM21/blob/main/Data101_(Chapter2).ipynb)
       * Varibles
       * Casting
       * Data Structure (list)
       * Loop
       * Condition (if statment)
       * Function
  *  [Pandas](https://github.com/team0243/DWDM21/blob/main/Data102(Chapter2).ipynb)
       * Read Data
       * Boxplot
       * Time Series plot
 * [Visualization](https://github.com/team0243/DWDM21/blob/main/Data_Visualization.ipynb)

   * Scatter plot
    * Plot (เป็นการพล็อตกราฟที่เชื่อมกัน)
    * Bar Chart
    * Histogram
 * [Distance Numpy](https://github.com/team0243/DWDM21/blob/main/Distance_Numpy.ipynb)
    * Numpy Array
    * Distance Matrix
  
**บทที่ 3 Data Preprocessing**
   * [Data Preprocessig](https://github.com/team0243/DWDM21/blob/main/Data103(Chapter3).ipynb)
   
     * การชี้ข้อมูลในตาราง
       
     * Missing Values
       
     * Select data by values [PD]
        
     * ต่อตารางแนวแกน Y [PD]
      
     * หา Outlier
     
     * การรวมตาราง (ต่อตารางในแนวแกน x)
   
     * Group by (pandas)
   
     * [PD] save ตารางเอาไปใช้ที่อื่น
       
     * [PD] การสร้างตาราง
         
         
**บทที่ 6 Association_Rules**
   * [Association Rules](https://github.com/team0243/DWDM21/blob/main/Chapter6_Association_Rules.ipynb)
   
     * มีประเทศสาขาของ Supermarket นี้ทั้งหมดกี่ประเทศ
     
     * วาดกราฟสรุปจำนวน items และ ยอดขายของแต่ละประเทศ

     * เพิ่มคอลัมน์ ยอดขาย (Quantity x UnitPrice)

     * จัดกลุ่มและหายอดขายรวม

     * จัดกลุ่มและหายอดขายรวม

     * ลบ records ที่ถูก cancel ออกไป

     * เตรียม data สำหรับ (Fequence Pattern) Association Rule

     * Apriori


**บทที่ 7 Classification**
  * [Decision Tree คำนวนมือ (การบ้าน)](https://github.com/team0243/DWDM21/blob/main/%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%9A%E0%B9%89%E0%B8%B2%E0%B8%99%20Decision%20Tree-%E0%B8%9C%E0%B8%AA%E0%B8%B2%E0%B8%99.pdf)
  * [Decision Tree](https://github.com/team0243/DWDM21/blob/main/Chapter7_Classification(Decision).ipynb)

      *  Load Data
     *   Train Model
      *  plot tree
     *   Advanced Tree
  * [K-Nearest Neighbor & Neural Network](https://github.com/team0243/DWDM21/blob/main/Chap_7_Classification_(KNN_NN).ipynb)
  
      *  Load data
      *  Split Data
       *  K-Nearest Neighbor (KNN)
       *  Retrain & Evaluate
        * Neural Network
     
   * [Evaluation](https://github.com/team0243/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb)
   
        *  Load data
         
        *  แบ่ง Data
        
        *  สร้าง Model ทำนาย
         
        *  Evaluation (classification_report, confusion_matrix, accuracy_score)



**บทที่ 8 Clustering**
  * [Clustering](https://github.com/team0243/DWDM21/blob/main/Chap8_Clustering.ipynb)
      
      * K-means
      * Clustering
      * Example application (Color Quantization)


**MiniExam**
[คลิกที่นี่](https://github.com/team0243/DWDM21/blob/main/MiniExam.ipynb)

**โครงงานกลุ่ม Project**
[คลิกที่นี่](https://github.com/team0243/DWDM21/blob/main/Project_SUKUNA.ipynb)

**โครงงานกลุ่ม นำเสนอ**
[คลิกที่นี่](https://github.com/team0243/DWDM21/blob/main/Project.pdf)

END

🅸 ​ 🅻🅾🆅🅴 ​ จารต้น





 




