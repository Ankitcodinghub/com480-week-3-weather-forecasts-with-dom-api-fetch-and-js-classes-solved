# com480-week-3-weather-forecasts-with-dom-api-fetch-and-js-classes-solved
**TO GET THIS SOLUTION VISIT:** [COM480 Week 3-Weather forecasts with DOM API, fetch and JS classes Solved](https://www.ankitcodinghub.com/product/com480-week-3-weather-forecasts-with-dom-api-fetch-and-js-classes-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96765&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COM480 Week 3-Weather forecasts with DOM API, fetch and JS classes Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<h1 id="weather-forecasts-with-dom-api-fetch-and-js-classes">Weather forecasts with DOM API, fetch and JS classes</h1>
In this exercise we display weather forecasts. We use JavaScript to make the presentation interactive: download the data from the internet and display it dynamically.

<h2 id="dom-api">DOM API</h2>
The DOM API allows JavaScript to completely control (edit, add, remove) the HTML objects constituting the web page. Please look at the example in&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/API/Document_object_model/Using_the_W3C_DOM_Level_1_Core">documentation</a>, we will be using similar operations.

We start, as usual, with the page in&nbsp;<a href="exercise/index.html"><code>exercise/index.html</code></a>. Please edit the files&nbsp;<code>exercise/exercise_weather.js</code>&nbsp;and&nbsp;<code>exercise/style_weather.css</code>&nbsp;to complete the exercise.

<ul>
<li><strong>On Click</strong>&nbsp;– The page contains a button with the id&nbsp;<code>btn-part1</code>.&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/API/Document/getElementById">Find it</a>&nbsp;and&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener">register a JS function to be executed</a>&nbsp;when the button is clicked. For now, the function should write “The button was clicked” to the console, so we can check if it executes properly upon click.
<strong>Note – Ensure the DOM has been loaded:</strong>&nbsp;we should make sure that the HTML has been loaded (and therefore, the button and other elements already exist) before we execute our script. Use the provided function&nbsp;<code>whenDocumentLoaded</code>&nbsp;to achieve that&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/Events/DOMContentLoaded">(about DOMContentLoaded event)</a>.
</li>
<li><strong>Show the temperatures</strong>&nbsp;– Given an array of forecast temperatures (such as the array&nbsp;<code>TEST_TEMPERATURES</code>), we want to display them in order. Create a function&nbsp;<code>showTemperatures(container_element, temperature_array)</code>&nbsp;such that:
<ul>
<li>Clears the&nbsp;<code>container_element</code>’s content, for example by setting the&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/API/Element/innerHTML"><code>innerHTML</code></a>&nbsp;to “”.</li>
<li>For each temperature value in&nbsp;<code>temperature_array</code>, it&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/API/Document/createElement">creates</a>&nbsp;a&nbsp;<code>&lt;p&gt;</code>&nbsp;element with the temperature value inside (for example&nbsp;<code>&lt;p&gt;13&lt;/p&gt;</code>). Please practoce a functional iteration method instead of an explicit&nbsp;<code>for</code>/<code>while</code>&nbsp;loop.</li>
<li>Places the&nbsp;<code>&lt;p&gt;</code>s in&nbsp;<code>container_element</code>.</li>
</ul>
Use that function to display the temperatures from&nbsp;<code>TEST_TEMPERATURES</code>&nbsp;in the div with id&nbsp;<code>weather-part1</code>.
</li>
<li><strong>Colors with CSS classes</strong>&nbsp;– Change the background color of the&nbsp;<code>&lt;p&gt;</code>&nbsp;depending on the temperature value. Create the classes&nbsp;<code>warm</code>&nbsp;and&nbsp;<code>cold</code>&nbsp;in&nbsp;<code>exercise/style_weather.css</code>&nbsp;with appropriate background colors. In your&nbsp;<code>showTemperatures</code>&nbsp;function, apply the appropriate CSS class to the created elements:
<ul>
<li><code>warm</code>&nbsp;for temperature 23 C or higher,</li>
<li><code>cold</code>&nbsp;for temperature 17 C and lower.</li>
</ul>
</li>
</ul>
<img decoding="async" data-src="task_images/temperatures_with_color.png" width="640" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">

<h2 id="js-classes">JS Classes</h2>
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes">Classes</a>&nbsp;allow us to organize our program around objects (“object-oriented programming”) and makes code easier to reuse – do the same actions with many objects. An object contains data (called properties) and functions (called methods).

First, we convert the code from the previous part into a class.

<ul>
<li>Create a&nbsp;<code>Forecast</code>&nbsp;class, which has the following properties:
<ul>
<li><code>container</code>&nbsp;– the element in which the temperatures will be written, the initial value should be given as an argument to the constructor,</li>
<li><code>temperatures</code>&nbsp;– current value of the temperature forecast, should be initialized to&nbsp;<code>[1,2,3,4,5,6,7]</code>.</li>
</ul>
Thus we create the object as&nbsp;<code>new Forecast(container_div)</code>. Instantiate the class, giving it the div with id&nbsp;<code>weather-part2</code>&nbsp;as the container.
</li>
<li>Add a&nbsp;<code>toString</code>&nbsp;method which writes its attributes to a string.</li>
<li>Add a&nbsp;<code>print</code>&nbsp;method which prints that string to the console.</li>
<li>Adapt&nbsp;<code>showTemperatures</code>&nbsp;to create a&nbsp;<code>show</code>&nbsp;method which takes no arguments and instead displays the object’s&nbsp;<code>temperatures</code>&nbsp;in its&nbsp;<code>container</code>.</li>
<li>Add a&nbsp;<code>reload</code>&nbsp;method which will be loading and displaying our data:
<ul>
<li>sets the&nbsp;<code>temperatures</code>&nbsp;property to&nbsp;<code>TEST_TEMPERATURES</code>&nbsp;(we will change it to real data later),</li>
<li>calls&nbsp;<code>show</code>.</li>
</ul>
</li>
<li>Upon the click of the button, call the&nbsp;<code>reload</code>&nbsp;method. Check if the temperatures are properly displayed.</li>
</ul>
Inheritance (<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes/extends"><code>extends</code></a>) allows us to create a sub-type with different behaviour (for example&nbsp;<code>class Dog extends Animal</code>). In our case, we will extend the&nbsp;<code>Forecast</code>&nbsp;class to change its data source: the child class&nbsp;<code>ForecastOnline</code>&nbsp;will download its data from the internet to provide a real forecast.

<ul>
<li>Create the class&nbsp;<code>ForecastOnline</code>&nbsp;which overrides the&nbsp;<code>reload</code>&nbsp;method and sets the temperature to&nbsp;<code>[2, 3, 4, 5, 6, 7, 8]</code>&nbsp;(we will get the real data in the next section). Instantiate&nbsp;<code>ForecastOnline</code>&nbsp;with div with id&nbsp;<code>weather-part3</code>&nbsp;and test if it shows the temperatures.</li>
</ul>
<img decoding="async" data-src="task_images/result_from_inheritance.png" width="640" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">

<h2 id="fetching-json-data-from-the-internet"><code>fetch</code>ing JSON data from the internet</h2>
The data displayed in a visualization is most often not part of the code. Instead it is stored in data files and downloaded separately from our server or an external service.

This data can be downloaded using the&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch">Fetch API</a>. Fetching is an asynchronous operation (we have to wait some time for the response), therefore it uses&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise">JS Promises</a>. Please read the linked documentation to see the examples.

We can get a forecast in the JSON format using Yahoo Weather, for example the query for Lausanne is:

<pre><code>http://query.yahooapis.com/v1/public/yql?format=json&amp;q=select * from weather.forecast where woeid in (select woeid from geo.places(1) where text="Lausanne") and u="c"</code></pre>
<ul>
<li>Use&nbsp;<code>fetch</code>&nbsp;to download the JSON from this URL, convert the JSON to a JS object and store the result to a global variable. Experiment with that value in the developer console to find out how to get the temperatures.</li>
<li>Create a function&nbsp;<code>yahooToTemperatures</code>&nbsp;which will extract the temperatures from the data. Since the API provides&nbsp;<code>low</code>&nbsp;and&nbsp;<code>high</code>&nbsp;temperature bounds, please calculate the mean of those values and return it as the result.</li>
<li>In&nbsp;<code>ForecastOnline</code>’s&nbsp;<code>reload</code>&nbsp;method, download the forecast from the specified URL and store it in the&nbsp;<code>temperatures</code>&nbsp;property, then call&nbsp;<code>show</code>. Please remember that&nbsp;<code>show</code>&nbsp;has to be executed after the data is downloaded (when the promise fires).</li>
</ul>
<h2 id="optional-interactive-choice-of-the-city">Optional: Interactive choice of the city</h2>
If you feel confident with DOM, fetch and classes, let’s combine them all into a more advanced system.

<ul>
<li>Create a class&nbsp;<code>ForecastOnlineCity</code>&nbsp;which allows fetching the forecast for any city:
<ul>
<li>Add some mechanism of inputting the city name, for example a method&nbsp;<code>setCity</code>.</li>
<li>Override&nbsp;<code>reload</code>&nbsp;to fetch the URL for the chosen city.</li>
<li>Override&nbsp;<code>show</code>&nbsp;to also display the name of the city. You can use&nbsp;<code>super.show()</code>&nbsp;to call the method in the parent class.&nbsp;<a href="https://developer.mozilla.org/en-US/docs/Web/API/Node/insertBefore"><code>insertBefore</code></a>&nbsp;can be useful to insert the city name before the temperature.</li>
</ul>
</li>
<li>Upon the click of the button with id&nbsp;<code>btn-city</code>, read the&nbsp;<code>.value</code>&nbsp;of the input with id&nbsp;<code>query-city</code>, then use your&nbsp;<code>ForecastOnlineCity</code>&nbsp;object to perform the query.</li>
</ul>
<img decoding="async" data-src="task_images/interactive.png" width="640" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload">
