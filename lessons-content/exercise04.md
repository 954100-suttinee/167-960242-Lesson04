## [Lesson03](../readme.md) > Exercise04:

1. Open class [Main](../src/main/java/org/dii/oop/Main.java) in package `main.java.org.dii.oop` and edit the code to call run() method from `exercise04`.


2. Edit class [Lesson](../src/main/java/org/dii/oop/exercise04/Lesson.java) in package `main.java.org.dii.oop.exercise04` and follow the instructions below:
    
      ### Products
      <table>
        <thead>
          <tr>
            <th>No.</th>
            <th>Code</th>
            <th>Brand</th>
            <th>Name</th>
            <th>Taste</th>
            <th>Author</th>
            <th>Published</th>
            <th>Type</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>1</td>
            <td>363369010</td>
            <td></td>
            <td>Democratic Education in a Conservative Age</td>
            <td></td>
            <td>Michael W. Apple</td>
            <td>1993</td>
            <td>Book</td>
          </tr>
          <tr>
            <td>2</td>
            <td>366817010</td>
            <td></td>
            <td>Giving Teaching Back to the Teachers</td>
            <td></td>
            <td>Robin Barrow</td>
            <td>1984</td>
            <td>Book</td>
          </tr>
          <tr>
            <td>3</td>
            <td>355056010</td>
            <td></td>
            <td>Learning Beyond The Classroom: Education for a Changing World</td>
            <td></td>
            <td>Tom Bentley</td>
            <td>1998</td>
            <td>Book</td>
          </tr>
          <tr>
            <td>4</td>
            <td>386926010</td>
            <td>C-Vitt</td>
            <td>ซีวิท รสเลมอน 140 มล. (แพ็ก 10 ขวด)</td>
            <td>เลมอน</td>
            <td></td>
            <td></td>
            <td>Food</td>
          </tr>
          <tr>
            <td>5</td>
            <td>383306010</td>
            <td>คิวมินซี</td>
            <td>คิวมินซี เคอร์คิวมิน+แอล-กลูตาไธโอน 150 มล. (แพ็ก 6 ขวด)</td>
            <td>ขมิ้นชัน</td>
            <td></td>
            <td></td>
            <td>Food</td>
          </tr>
          <tr>
            <td>6</td>
            <td>397208010</td>
            <td>เพรสแอนด์เชค</td>
            <td>เพรสแอนด์เชค คอลลาเจน วิตซี 3.5 กรัม (แพ็ก 12 กล่อง)</td>
            <td>คอลลาเจน วิตามินซี</td>
            <td></td>
            <td></td>
            <td>Food</td>
          </tr>
        </tbody>
      </table>
   
    - Create the [Product](../src/main/java/org/dii/oop/exercise04/Product.java) class and place it in the `main.java.org.dii.oop.exercise04` package, then create two different constructors to initialize the attributes.
   
    - According to the different types of products (Book/Food) as shown in the products table, use the two constructors to differenciate 
   
    - Instance objects of all products in the table and store them in an array object.
      ```
      Product[] products = new Product[6];  // Create an array object with six elements
      products[0] = ...;
      products[1] = ...;
      ...
      products[5] = ...;
      ```
    - Modify [Lesson](../src/main/java/org/dii/oop/exercise04/Lesson.java) class to allow the user to display the list of products depending on the types of products.
      ```
      DII shop:
      1. Book
      2. Food
      Choose the number [1/2] to display product:
      ```
    - The program asks the user to continue running by typing the character 'y' or 'n'.
      ```
      Do you want to continue [y/n]:
      ```

3. Run the code.
    - An example when the user chooses the number `1`.
      ```
      DII shop:
      1. Book
      2. Food
      Choose the number [1/2] to display product: 1
      Code: 363369010
      Author: Michael W. Apple
      Book name: Democratic Education in a Conservative Age
      Published: 1993
      -----------------------------
      Code: 366817010
      Author: Robin Barrow
      Book name: Giving Teaching Back to the Teachers
      Published: 1984
      -----------------------------
      Code: 355056010
      Author: Tom Bentley
      Book name: Learning Beyond The Classroom: Education for a Changing World
      Published: 1998
      -----------------------------
      Do you want to continue [y/n]:
      ```
    - An example is when the user decides to continue and choose the number '2'.
      ```
      DII shop:
      1. Book
      2. Food
      Choose the number [1/2] to display product: 1
      Code: 363369010
      Author: Michael W. Apple
      Book name: Democratic Education in a Conservative Age
      Published: 1993
      -----------------------------
      Code: 366817010
      Author: Robin Barrow
      Book name: Giving Teaching Back to the Teachers
      Published: 1984
      -----------------------------
      Code: 355056010
      Author: Tom Bentley
      Book name: Learning Beyond The Classroom: Education for a Changing World
      Published: 1998
      -----------------------------
      Do you want to continue [y/n]: y
      
      DII shop:
      1. Book
      2. Food
      Choose the number [1/2] to display product: 2
      Code: 386926010
      Brand: C-Vitt
      Book name: ซีวิท รสเลมอน 140 มล. (แพ็ก 10 ขวด)
      Taste: เลมอน
      -----------------------------
      Code: 383306010
      Brand: คิวมินซี
      Book name: คิวมินซี เคอร์คิวมิน+แอล-กลูตาไธโอน 150 มล. (แพ็ก 6 ขวด)
      Taste: ขมิ้นชัน
      -----------------------------
      Code: 397208010
      Brand: เพรสแอนด์เชค
      Book name: เพรสแอนด์เชค คอลลาเจน วิตซี 3.5 กรัม (แพ็ก 12 กล่อง)
      Taste: คอลลาเจน วิตามินซี
      -----------------------------
      Do you want to continue [y/n]: n
      ```
