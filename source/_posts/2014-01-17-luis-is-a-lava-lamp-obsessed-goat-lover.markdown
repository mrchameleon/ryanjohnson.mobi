---
layout: post
title: "testing out my new octopress blog"
date: 2014-01-17 17:04:56 -0500
comments: true
categories:
---

``` ruby test code sample http://github.com/mrchameleon/Car-lot/blob/master/app/models/car.rb github-link 

class Car < ActiveRecord::Base

  versioned

  belongs_to :customer


  validates_presence_of :make, :model, :year

  def to_s
    "#{self.year} #{self.make} #{self.model}, Inventory ##{self.id}"
  end

end

```

The path of the righteous man is beset on all sides by the iniquities of the selfish and the tyranny of evil men. Blessed is he who, in the name of charity and good will, shepherds the weak through the valley of darkness, for he is truly his brother's keeper and the finder of lost children. And I will strike down upon thee with great vengeance and furious anger those who would attempt to poison and destroy My brothers. And you will know My name is the Lord when I lay My vengeance upon thee.

<!-- please do not remove this line -->

<div style="display:none;">
<a href="http://slipsum.com">lorem ipsum</a></div>
