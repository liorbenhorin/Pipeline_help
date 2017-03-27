#Hotkeys and Shelf buttons

You can map the below codes to either hotkeys or shelf buttons

###Save version
```
def pipeline_save_version():
    import logging
    logger = logging.getLogger(__name__)
    try:
        pipeline_win = pipeline.apps.pipeline_main.pipeLineUI.instances
        print pipeline_win
        if len(pipeline_win) == 1:
            pipeline_win[0].version_save()
        else:
            logger.info('Not saving: Too many pipeline instances.')

    except:
        logger.info('Not saving: no Pipeline instance found')


pipeline_save_version()
```

