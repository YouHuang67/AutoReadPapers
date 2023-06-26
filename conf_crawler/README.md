# Usage
在`conf_crawler`目录下，运行
`scrapy crawl [conference] -a years=[year]  -s JOBDIR=[job directory]`
比如`scrapy crawl cvpr -a years=2023  -s JOBDIR=out_jobs`，
会生成`data.csv`文件