# Changelog

## 0.1.6 (2026-08-26)

Bug fix: Predicates or callbacks for the map, filter, find, findIndex, findLast, findLastIndex, every, some, forEach, reduce, reduceRight, and flatMap functions hand the array back as a third argument. However, the array was the "raw" array instead of the `FastShiftArray`. The index handed back was into the `FastShiftArray`, and so the indexes did not line up after shifts. Now the third argument is the `FastShiftArray`.

## 0.1.5 (2026-08-22)

Fixed a bug where shift would set the new array to the removed values (ugh).

## 0.1.4 (2026-04-04)

Fixed links to docs (deja-vu).

## 0.1.3 (2026-04-04)

Fixed links to docs.

## 0.1.2 (2026-04-04)

1. Added code docs
2. Added workflow for generating and publishing docs to github-pages

## 0.1.1 (2026-04-04)

- Fixed link to git repo in the package.json file

## 0.1.0 (2026-04-04)

- Initial release
