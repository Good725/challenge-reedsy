Reedsyapplications.



Answer 1.

I am a full-stack web developer who has 8 years experience in Software engineering.
My web languages are Ruby, PHP, and Javascript.
My back-end stacks: Ruby on rails, laravel
front-end stacks: React, HTML/CSS
Database stacks: Postgresql, MySQL
With my past projects, I am able to proof my skills.
On all projects, I satisfied my clients and so I could get long-term work.
I am very serious in deadline and quality.
These are my past projects using Ruby on Rails.
https://mealz.com/
https://slaytlive.com
https://velvetjobs.com
And also I shared my code sample.
My major achievement was to take part in building one enormous ecommerce project as a software engineer.
In my free time, my hobby is Sport and Computer games.
If I am hired, I will do all my best for this project as a Web developer.
Looking forward to hearing from you soon.
Thank you.


Answer 2.

class Feed
  def initialize(user)
    @user = user
  end

  def retrieve
    author_ids = user.followed_authors.pluck(:id)
    upvoted_book_ids = user.upvotes.pluck(:book_id)
    Book.where("author_id in ? or id in ?", author_ids, upvoted_book_ids).order_by(published_on: :desc)
  end
end


- User has a has_many "followed_auth" relationship with authors
- User has a has_many "upvotes" relationship with upvotes
- Book has a belongs_to relationship with Author.


Answer 4.
Recommendation systems can be a whole world in itself.
I may wanna look into the subject of fuzzy logic.
