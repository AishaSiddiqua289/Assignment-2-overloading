#!/usr/bin/env python
# coding: utf-8

# # Assignment No 2
# ## overloading
# ### Piaic181221

# In[22]:


class Calculation():
        def sum(self,*num):
            return sum(num)
        
        


# In[24]:


m1 = Calculation()
print(m1.sum(7,9))
print(m1.sum(6,4,9))
print(m1.sum(7.9,6,45))
print(m1.sum())
print(m1.sum(45,99,89,55))


# In[ ]:




