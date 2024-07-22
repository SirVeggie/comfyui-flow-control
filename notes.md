might not want to clear node cache for blocked nodes,
can lead to unnecessary execution when swapping between branches repeatedly

current code doesn't recognize when some primitive inputs change?
- if parents are cached, we should somehow check if widgets have changed