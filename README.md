package system.test.check5

import future.keywords.if

default allowuser := false

allowuser if input.perm == "world"
