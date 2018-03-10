@Library('libpipelines@preproduction') _

hose {
    EMAIL = 'qa'
    MODULE = 'stratio-parent'
    DEVTIMEOUT = 20
    RELEASETIMEOUT = 20
    REPOSITORY = 'stratio-parent'
    FOSS = true
    
    DEV = { config ->        
            doPackage(config)
            doDeploy(config)
    }
}
