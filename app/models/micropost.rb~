class Micropost < ActiveRecord::Base
  attr_accessible :Content, :user_id
  belongs_to :user
  validates :Content, :length => { :maximum => 140 }
  
end
