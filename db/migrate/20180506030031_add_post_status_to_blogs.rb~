class AddPostStatusToBlogs < ActiveRecord::Migration[5.1]
  def change
    remove_column :blogs, :integer
    remove_column :blogs, :status
    add_column :blogs, :status, :integer,default:0
  end
end
