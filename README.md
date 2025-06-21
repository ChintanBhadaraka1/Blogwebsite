user
blog
category
comment
likes

========= functionality =

user register
user login
user listing

---- blog

view
edit
listing
add
delete
action (published,Reject)

--- categories
listing
exit
add
delete

---- likes &  comment

listing
action(Reject,Approval)



Table Design 

User:
- name
- email
- phone_no
- profile_pic
- role
- status

category 

- name
- slug
- parent_id (sub-category)
- status

Blog :

- name(heading)
- slug
- description
- status
- user_id
- category_id
- sub_category_id
- images

Likes :

- blog_id
- user_id
- action

Comment :

- blog_id
- user_id
- comment_id
- comment
- status



