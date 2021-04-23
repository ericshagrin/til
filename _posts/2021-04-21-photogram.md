 belong_to automatically validates presense of the foreign key, unless you add "optional: true" to the belong_to statement
 
 for every belonds_to you need a corresponding has_many
 
 
 for adding a column to a table
  - https://blog.arkency.com/how-to-add-a-default-value-to-an-existing-column-in-a-rails-migration/
  - change_column_default(
      table_name,
      column_name,
      default
    )
    
scopes
- a scope amkes it so instead of using a where or order with the exact same thing you call one thing once and it serves the smae function (like a method almost)


Enum col 
- Like enum in c, gives you a list of terms and what they're represented by
- It can make it so only a certain number of items can be part of database column
- Defines scopes for you (including a positive or negative for each on) 
    - # assume follow_request is a valid and pending
    - follow_request.accepted? # => false
    - follow_request.accepted! # sets status to "accepted" and saves
