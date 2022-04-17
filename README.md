# MyArticles - Rails API Example

         Prefix Verb   URI Pattern                     Controller#Action
api_v1_articles GET    /api/v1/articles(.:format)      api/v1/articles#index
                POST   /api/v1/articles(.:format)      api/v1/articles#create
 api_v1_article GET    /api/v1/articles/:id(.:format)  api/v1/articles#show
                PATCH  /api/v1/articles/:id(.:format)  api/v1/articles#update
                PUT    /api/v1/articles/:id(.:format)  api/v1/articles#update
                DELETE /api/v1/articles/:id(.:format)  api/v1/articles#destroy
