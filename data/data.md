each of these should be a sql file. I've stuck the January 2017 file in here. 
It's indexed by URL. I didn't bother to value_counts the URLs
then realized the URLs might be duplicated over multiple days so added a _month_day to the URL so if you want to
do a get request, realiz it's [url]_MM_DD so can just do a [:-6]

Articles are in a table called article, it uses the default GDELT v1 labels
