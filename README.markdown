A [Giter8][g8] template to show an example on how to use Spark ,Akka-http along with Couchbase by making a REST Service.

Sprak-akka-http-couchbase-starter-kit
---------------------------------------

This project will hep you to make CRUD operations using your own couchbase and Spark installations.

#Steps for running the Project:

1. Make two buckets i.e userBucket and testUserBucket.
2. Make View using the userddoc.ddoc file present in resources. 
3. Make a primary index on both the buckets i.e userBucket and testUserBucket.
4. Now if you want to run the test case execute "./activator clean compile test"
5. If you want to run the project execute "./activator clean compile run"

Template license
----------------
Written in ​ 2017​ by ​ [Knoldus Software LLP](http://knoldus.com)

To the extent possible under law, the author(s) have dedicated all copyright and
related
and neighboring rights to this template to the public domain worldwide.
This template is distributed without any warranty. See
<http://creativecommons.org/publicdomain/zero/1.0/>.
[g8]: http://www.foundweekends.org/giter8/
