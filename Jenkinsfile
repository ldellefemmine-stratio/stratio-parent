@Library('libpipelines@feature/multibranch') _

hose {
    EMAIL = 'qa'
    MODULE = 'stratio-parent'
    DEVTIMEOUT = 20
    RELEASETIMEOUT = 20
    REPOSITORY = 'stratio-parent'
    
    DEV = { config ->        
            doDeploy(config)
    }
}
