# logomotive
# logomotive  Minimal structured logger with levels, tags, a `@log_call` decorator, and `with logger.section(...)`.  ## Usage  ```python from logomotive import Logger  logger = Logger("run.log", verbose=20, min_level=20) logger.info("hello")  with logger.section("prep", timing=True):     ... ```
