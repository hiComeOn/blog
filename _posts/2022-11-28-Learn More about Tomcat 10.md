---
title: "Learn More about Tomcat 10"
date: 2022-11-28
---
From [Tomcat’s documentation](https://tomcat.apache.org/download-10.cgi), we can know there is a significant breaking change between Tomcat 9.0.x and Tomcat 10.0.x. The Java package used by the specification APIs has changed from javax.* to jakarta.* which may cause backward compatibility problems when upgrading. And they also provide a migration tool to help this change (we will introduce this tool in the next section).