## Company Info Crawler

Ruby on rails application to extract generic information from the target website. HttParty is used to extract the content from the website , parse using Nokogiri and indexed using Elastic Search. The process is carried out as background task using sidekiq. Latent Dirichlet allocation is used to extract the topics from the content indexed based on the word search and most informational content is returned based on the query.

