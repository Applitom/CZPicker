### v0.3.5 - 2015-07-21
#### Changed
- Change delegate & dataSource methods names to conform to apple's guideline and avoid error in swift.(methods' names start with 'CZPicker' to 'czpicker')[#5](https://github.com/chenzeyu/CZPicker/issues/5)
- Make picker higher in landscape mode.

### v0.3.4 - 2015-07-20
#### Fixed
- Fixed multiple selection mode cell selection not remembered issue. [#8](https://github.com/chenzeyu/CZPicker/issues/8)

### v0.3.3 - 2015-07-20
#### Fixed
- Listen to orientation change when needed. (App supports landscape & portrait)
- Animate picker only on supported orientations.
- Fixed multiple selection mode cell selection not remembered issue. [#8](https://github.com/chenzeyu/CZPicker/issues/8)

### v0.3.2 - 2015-07-16
#### Changed
- Changed return type of ```CZPickerView:titleForRow:``` to NSString.

#### Added
- Added ```CZPickerView:attributedTitleForRow``` to support attributed row title, reference: [#3](https://github.com/chenzeyu/CZPicker/issues/3)

### v0.2.2 - 2015-07-14
#### Added
- Added ```allowMultipleSelection``` flag to support multiple selections, reference: [#1](https://github.com/chenzeyu/CZPicker/issues/1)

### v0.2.1 - 2015-07-14
#### Fixed
- Fixed orientation issue, reference: [#2](https://github.com/chenzeyu/CZPicker/issues/2).
