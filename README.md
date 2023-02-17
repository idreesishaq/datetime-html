# datetime-html
deep comprehension of the use of datetime function in html

## Why we use the time tag in html?
well this question may comes in your mind that why we use time tag in html to show the time to the users. Although we can show the date or time by any of the text formatting tag in html, html has an specific tag ```<time></time>``` to only show the date and time to the user or reader but also to give semantic meaning and make it understandable to computer.


1. We can give date in any format for human understanding, but for there is an specific format to make it machine readable.
The format is: __YYYY-MM-DD__. The datetime attribute (which is not a global attribute and can only be used in time tag) is used to time in compter readable format.

```
<time> Feb 17, 2024 </time>
<time datetime="2024-02-17"> Feb 17, 2024 </time>
<time datetime="2024-02-17"> 17 Feb 2024 </time>
<time datetime="2024-02-17"> Feb 17 </time>
```

2. We can also give time like this __hh-mm-ss__
and also fractions of seconds like this __hh-mm-ss.ddd__

```
<time datetime="07:00"> 7:00 am </time>
<time datetime="20:15"> 8:15 pm </time>
<time datetime="12:30"> afternoon </time>
```

3. We can also add time zone in this way__hh-mm-ss.dd+-hh:mm__
```
<time datetime="14:15-05:00"> 2:15 pm New York time </time>
```

4. To give data and time together we can use __T__ or __space__ to seperate date and time.
```
<time datetime="2024-02-17T07:00-05:00"> 17 Feb 2024, 7:00 am New York Time </time>
```

OR
```
<time datetime="2024-02-17 07:00-05:00"> 17 Feb 2024, 7:00 am New York Time </time>
```
