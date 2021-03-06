# Changelog

## 0.2.7

- rebind `windoze` instance to modal element on open (so shared modals bind properly to their respective triggers)

## 0.2.6

- option to disable automatic focusing on first input when modal is shown

## 0.2.5

- allow lightboxing to be set manually via option or data attribute
- fix a bug when lightboxing an element would create multiple new elements

## 0.2.4

- Add `destroy.windoze` event, improve tests around events
- Add missing -moz and prefixless transitions to default stylesheet

## 0.2.3

- Pass event through to all callbacks
- Fix bug where overlapping calls weren't turning off old events

## 0.2.2

- add `open.windoze` and `close.windoze` events
- add `relocate_modal` option
- fix bug involving missing but expected `href`

## 0.2.1

- properly detect hrefs if click target is child of a link
- change modal div positioning to not be absolute anymore
- modals now empty before starting ajax load
- 'wdz-modal-open' class is now removed via overlay hiding so swapping modals doesn't trigger it
- links directly to images now load image into a plain <article>

## 0.2

- Rework default styles to position child of modal layer and allow outside modal to scroll

## 0.1

- Kept the name, rewrote from scratch
