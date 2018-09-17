## Method-Trace-Analyser

Java based GUI application to parse and compare multiple trace files, to help debugging the code.
Method trace is used for post-mortem debugging. It consists of timestamp of entry and exit points for each method invocation. they may also contain stack-trace for each invocation.
In case of functionality issues, comparing of the data is used for debugging.

#Functionalities included:
1. Compare two trace files: one from failing and passing case each and find out the anomaly.
2. Parse one or more trace file and suggest anomalies - I.e. Flag methods which are not completing their execution / Taking longer to execute. This will be helpful in addressing hang and performance related problems.
3. Parse one or more trace files and create a tabular and graphical view for the number of times each method is invoked. Comparative view in case of multiple files.
4. Compare code-flow and stack trace for failing and passing case and find anomalies.

#Technology Stack:
Java,
IBM Java Method trace

#Team Details:
Anupriya Singh  (anupriya228@gmail.com)
Jyoti Pandey    (jyotipandeyjyoti48@gmail.com)
Ronika Das      (ronikadas@gmail.com)
Nidhi Wadhwa    (ndhwadhwa60@gmail.com)
