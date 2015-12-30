# Charts Web App

Inspired by lessons I learned from my favorite undergrad professor at UTSA, Ronald Sweet, I made this simple web app that replicates a process he showed us in class. The basic goal is to show how looking at the Beta of a given stock at one point in time can be misleading. The app calculates the 3-Year Rolling Beta and plots how those Beta values over time for a given set of stocks. For many popular stocks, this metric varies wildly over the life of the company.

The original version was written in PHP in 2012, with minor changes made during a migration to a new server in late 2015. I also began writing a pure JavaScript version at that time, though have not gotten anywhere close to done. The finished and working PHP version should be reasonably easy to copy onto a web server running PHP (keeping all files within the same folder) to get it working. You can find the code for the PHP version [here](php/) and the JavaScript version (still a work in progress) [here](js/). The current PHP version is running on my server and can be found at http://charts.zachmueller.com.