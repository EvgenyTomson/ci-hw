---
name: Release issue template
about: Create new release
title: ''
labels: New Release
assignees: ''

---

---
title: RELEASE {{ env.RELEASE_NO }}
---

Release date: {{ env.RELEASE_DATE | date('dddd, MMMM Do') }}  

Author: {{ env.RELEASE_AUTHOR }}  

Changes:  
{{ env.RELEASE_CHANGELOG }}
