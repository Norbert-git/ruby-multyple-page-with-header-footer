# README

Create multyple pages with header and footer on all pages

Header and Footer:

- go to app/views/application.html.erb

<body>
Add Header and Footer here for all pages
</body>

Create 2nd 3rd ... pages.

- app/views/home

  - create file: about.html.erb

- app/controller/home_controller.rb

  - create anoter function
    def about
    end

- config/routes.rb add to file
  - get 'home/about'

Go to Localhost:3000/home/about

Should see the about page wit the header and footer.
