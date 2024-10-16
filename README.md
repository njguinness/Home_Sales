# home-sales

  <div class="description user_content "><div id="bootcamp">
<img style="display: none;" src="https://static.bc-edx.com/data/dl-1-2/m22/lms/img/banner.jpg" alt="lesson banner">
    <p>In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.</p>
    <h3>Before You Begin</h3>
    <ol>
        <li>
            <p>Create a new repository for this project called, <code>Home_Sales</code>. <strong>Do not add this homework to an existing repository</strong>.</p>
        </li>
        <li>
            <p>Clone the new repository to your computer.</p>
        </li>
        <li>
            <p>Push your changes to GitHub.</p>
        </li>
    </ol>
    <h3>Files</h3>
    <p>Download the following files to help you get started:</p>
    <p><a href="https://static.bc-edx.com/data/dl-1-2/m22/lms/starter/Starter_Code.zip">Module 22 Challenge files</a></p>
    <h3>Instructions</h3>
    <ol>
        <li>
            <p>Rename the <code>Home_Sales_starter_code.ipynb</code> file as <code>Home_Sales.ipynb</code>.</p>
        </li>
        <li>
            <p>Import the necessary PySpark SQL functions for this assignment.</p>
        </li>
        <li>
            <p>Read the <code>home_sales_revised.csv</code> data in the starter code into a Spark DataFrame.</p>
        </li>
        <li>
            <p>Create a temporary table called <code>home_sales</code>.</p>
        </li>
        <li>
            <p>Answer the following questions using SparkSQL:</p>
            <ul>
                <li>
                    <p>What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.</p>
                </li>
                <li>
                    <p>What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.</p>
                </li>
                <li>
                    <p>What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.</p>
                </li>
                <li>
                    <p>What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.</p>
                </li>
            </ul>
        </li>
        <li>
            <p>Cache your temporary table <code>home_sales</code>.</p>
        </li>
        <li>
            <p>Check if your temporary table is cached.</p>
        </li>
        <li>
            <p>Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.</p>
        </li>
        <li>
            <p>Partition by the "date_built" field on the formatted parquet home sales data.</p>
        </li>
        <li>
            <p>Create a temporary table for the parquet data.</p>
        </li>
        <li>
            <p>Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.</p>
        </li>
        <li>
            <p>Uncache the <code>home_sales</code> temporary table.</p>
        </li>
        <li>
            <p>Verify that the <code>home_sales</code> temporary table is uncached using PySpark.</p>
        </li>
        <li>
            <p>Download your <code>Home_Sales.ipynb</code> file and upload it into your "Home_Sales" GitHub repository.</p>
        </li>
