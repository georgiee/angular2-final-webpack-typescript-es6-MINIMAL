# A minimal runnable Angular2 configuration based on webpack with typescript & es6

I dissected this full-blown version:
https://github.com/preboot/angular2-webpack

and rebuild it (well mainly package.json and webpack config) from scratch with the goal to run the angular applicaiton and print a string.

Difficulties I encountered:

+ Don't miss the polyfills.ts or you get the error with __decorate is not defined
+ Don't forget the DashboardPlugin or you won't get any reports
+ Don't forget to add HtmlWebpackPlugin to auto include the inlined files. Yeah this was stupid and killed some time :)

