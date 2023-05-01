# Random-Tales
import random
who = ['a rabbit', 'a dog', 'a fox', 'a turtle','a cat','a bird']
name = ['Marli', 'Dawn','James', 'Henry', 'Stryker']
happened = ['made new acquaintances','Eats a pizza', 'found a lost watch', 'solved a problem', 'posted a blog']
went = ['cinema', 'university','seminar', 'school', 'laundry']
residence = ['Bahamas','India', 'Germany', 'Venice', 'England']
when = ['A few years ago', 'Yesterday', 'Last night', 'A long time ago','On 20th Jan']
print(random.choice(who) + ', ' + random.choice(name) + ' that lived in ' + random.choice(happened) + ', went to the ' + random.choice(went) + ' and ' + random.choice(residence))
