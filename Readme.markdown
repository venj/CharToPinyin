CharToPinyin
============

This is a small Chinese pinyin library based on Sunrise Spell, a C# implementation.

Usage
-----

Import source files to your project. In code, use:

```objc
// Will return: zw
NSString *result = [[CharToPinyin shared] translate:@"中文" withSpaceString:@"" options:CPSpellOptionsFirstLetterOnly];
```

Now only have one convinient method `- abbreviation:` for first letter only abbreviation.

```objc
// Will return: zw
NSString *result = [[CharToPinyin shared] abbreviation:@"中文"];
```

License
-------

Copyright (c) 2012 venj <ersaclarke@gmail.com>

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 2 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details. 

You should have received a copy of the GNU General Public License along with this program; if not, write to the Free Software Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111 1307 USA. In case your copy of CharToPinyin does not include a copy of the license, you may find it online at [http://www.gnu.org/copyleft/gpl.html](http://www.gnu.org/copyleft/gpl.html)


Acknowledgement
---------------

Thanks to the author of SunriseSpell - A Chinese pinyin library, Copyright (C) 2004 mic  <mic4free@hotmail.com>
