# stopwatch1
stopwatch project
i start with html file 

## HTML

<body>
    <div class="box"> this line i use for box which is use in stopwatch
        <h2 class="heading"> Stopwatch</h2> this line i use for heading which is i use for mention a stopwatch
        <h1 id="stopwatch">00 : 00 : 00</h1> this for staring with 00
        <button onclick="start()" style="background-color: green;">Start</button> this line i use for connect function with java script i use three functions
        <button onclick="stop()" style="background-color: red;">Stop</button>
        <button onclick="reset()" style="background-color: royalblue;">Reset</button>
    </div>



    <script src="index.js"></script> this line i use for connecting our js file with html
    
</body>
</html>

# CSS
*
{
    margin: 0px;
    padding: 0px;
    font-family: cursive;
    box-sizing: border-box;
} 

body
{
    background-color: royalblue;
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;


}

.box
{
    background-color: white;
    height: fit-content;
    width: fit-content;
    padding: 50px;
    border-radius: 60px 10px 60px 10px ;
    box-shadow: 5px 5px 10px white;


} this code i use for desinging box you see wath i use 
.heading
{
    color: rgb(10, 154, 156);
    text-align: center;


} this code i use for heading 

h1
{
    font-size: 50px;

}
button
{
    border: none;
    outline: none;
    font-size: 20px;
    padding: 15px;
    border-radius: 5px;
    margin: 15px;
    color: white;
    cursor: pointer;

} finally i use this  code for desing a botton 
