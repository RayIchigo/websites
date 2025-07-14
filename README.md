# websites
This project contains a basic two-page website built using HTML. The pages are linked together for navigation, and the site is hosted locally using XAMPP as the server environment.

##  How to Run the Website Locally

1. **Download and Install XAMPP**  
    [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html)

2. **Start Services in XAMPP**  
   - Open **XAMPP Control Panel**
   - Click **Start** next to **Apache**
   - Click **Start** next to **MySQL** 

3. **Create Your Website Files**
   - Use **Notepad** (or any code editor) to create `index.html`
   - Create the second page `secpage.html` the same way and save it in the same folder.

4. **Link Between Pages**
   - Inside `index.html`, use a link or button to navigate to `secpage.html`:
     ```html
     <a href="secpage.html">Go to Second Page</a>
     ```
     
##  Tools Used

- HTML5
- Notepad (or any basic text editor)
- XAMPP (Apache and MySQL servers)

## NOTE

- **index.html** is the main entry point of the website.
- It includes a **button** that links to **secpage.html**.
- Both files are stored in the same folder (`admin`) inside `htdocs`.

