## Preview

![Preview](preview.gif)

## Properties

    var itemHeight: CGFloat
    var spacing: CGFloat
    var maximumNumberOfRows: Int

## Methods

    func register(_ cellClass: AnyClass?, forCellWithReuseIdentifier identifier: String)

    func dequeueReusableCell(withReuseIdentifier identifier: String, for index: Int) -> UICollectionViewCell

    func reloadData()

## Delegate

    func slidingCollectionView(_ slidingCollectionView: SlidingCollectionView, widthForItemAt index: Int) -> CGFloat

    func slidingCollectionView(_ slidingCollectionView: SlidingCollectionView, didSelectItemAt index: Int)


## Data Source

    func numberOfItems(in slidingCollectionView: SlidingCollectionView) -> Int

    func slidingCollectionView(_ slidingCollectionView: SlidingCollectionView, cellForItemAt index: Int) -> UICollectionViewCell

## Todo

- [ ] Move to Carthage & Cocoapods
- [ ] Support vertical axis
