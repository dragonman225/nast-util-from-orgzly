# nast-util-from-orgzly

### Moved to [nast/packages/nast-util-from-orgzly](https://github.com/dragonman225/nast/tree/master/packages/nast-util-from-orgzly)

Parse org-mode file from [Orgzly](http://www.orgzly.com/) app with [orga](https://github.com/xiaoxinghu/orgajs) and transform to NAST, which can later be rendered to HTML using [nast-util-to-html](https://github.com/dragonman225/nast-util-to-html).

### Component mapping from oast to nast

| oast type |                nast type                 |
| :-------: | :--------------------------------------: |
|   root    |                   page                   |
| paragraph |                   text                   |
|  section  |                  toggle                  |
|   list    |      numbered_list or bulleted_list      |
| list.item | numbered_list_item or bulleted_list_item |

