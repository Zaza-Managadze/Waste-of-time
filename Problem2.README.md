# If you don't want to waste your time, don't solve this problem.

## 2) (yeah, I skipped the 1st one):<br />
This problem is not worth wasting time on, but you can try anyway if you have nothing to do.<br />
You have a CountDown component that displays the time left untile a given deadline with the following format: **Days:Hours:Minutes:Seconds**. The trailing zeros can be discarded. For example, if there are 0 days 0 hours, M minutes, and S seconds left, then you should display the time as follows **M:S**.<br />
You have two tasks:<br/>
### 1.
Implement the display function so that the remaining time will be renedered in the format specified above.
### 2.
Implement a class decorator that will update the clock. **DO NOT write anything inside the CountDown component other than implementing the display function**. You must pass the deadline as a parameter to the decorator. It can be of type string, number, or Date. **Ex: "4/13/2021 16:50:00", 1618319421628, new Date("Tue Apr 13 2021 17:10:06 GMT+0400 (Georgia Standard Time)")**. When the time is up, the decorator **must** alert the user with the text "Time is up!" **before** the finish page component will be rendered.

Problem:
https://codesandbox.io/s/condescending-moon-uf9qv?file=/src/CountDown.tsx
<br />
Solution:
https://codesandbox.io/s/reverent-rgb-53png?file=/src/CountDown.tsx
<br />
