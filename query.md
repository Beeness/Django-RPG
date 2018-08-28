[] ./manage.py shell
from charactercreator.models import Character
x = Character.objects.all()
len(x)
answer: 302

[]How many of each specific subclass?
*Fighters
from characatercreator.model import Fighter
len(Fighter.objects.all())

68 fighters

*Mages
from characatercreator.model import Mage
len(Mage.objects.all())

108 mages

*Cleric
from characatercreator.model import Cleric
len(Cleric.objects.all())

75 cleric

*Thief
from characatercreator.model import Thief
len(Thief.objects.all())

51 thiefs

*Necromancer
from characatercreator.model import Necromancer
len(Necromancer.objects.all())

11 necromancer

[]How many total Items?
from armory.models import Item
len(Item.objects.all())

174 total items

[]How many of the Items are weapons? How many are not?
from armory.models import Weapon
len(Weapon.objects.all())

37 total items are weapons
Item.objects.count() - Weapon.objects.count()
137 total items are not weapons

[]On average, how many Items does each Character have?


[]On average, how many Weapons does each character have?
