# 1st-Web-Tech
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Simple Web Design</title>
</head>
<body>

<hr>
<center>
    <h1>HEADING</h1>
    Reg.no: URK24CS9035
</center>
<hr>

<h2>Heading1</h2>
<h3 id="sub1">Sub heading1</h3>
<p>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
    Nulla quam velit, vulputate eu pharetra nec, mattis ac neque.
    Duis vulputate commodo lectus, ac blandit elit tincidunt id.
    Sed dignissim tortor sed elit tristique.
</p>

<a href="mailto:yourname@example.com">E-MAIL</a><br>
<a href="tel:+910000000000">Phone no</a><br><br>

<img src="https://www.w3.org/html/logo/downloads/HTML5_Logo_512.png" alt="HTML5 Logo" width="80">

<h2>Heading2</h2>
<h3 id="sub2">Sub heading2</h3>

<table border="1" align="center">
    <tr>
        <th>Row1-Col1</th>
        <th>Row1-Col2</th>
        <th>Row1-Col3</th>
        <th rowspan="4">Row1,2,3,4 Col4</th>
    </tr>
    <tr>
        <td>Row2-Col1</td>
        <td colspan="2">Row2-Col2 &amp; Col3</td>
    </tr>
    <tr>
        <td>Row3-Col1</td>
        <td colspan="2">Row3-Col2 &amp; Col3</td>
    </tr>
    <tr>
        <td>Row4-Col1</td>
        <td colspan="2">Row4-Col2 &amp; Col3</td>
    </tr>
    <tr>
        <td colspan="2">Row5-Col1 &amp; Col2</td>
        <td colspan="2">Row5-Col3 &amp; Col4</td>
    </tr>
    <tr>
        <td colspan="4">Row6-Col1,2,3 &amp; Col4</td>
    </tr>
</table>

<br>
<p>This is a fairly complicated mixed list</p>
<ul>
    <li>First Item
        <ol>
            <li>First item of nested list</li>
            <li>Second item of nested list
                <ul>
                    <li>This item is nested even further</li>
                    <li>And this one too
                        <ol type="A">
                            <li>First item of another numbered list</li>
                            <li>Second item of another numbered list</li>
                        </ol>
                    </li>
                </ul>
            </li>
        </ol>
    </li>
    <li>Second Item</li>
    <li>Third Item</li>
</ul>

<hr>
<a href="#sub1">Go to Subheading1</a>
<a href="#sub2">Go to Subheading2</a>
<hr>

</body>
</html>
