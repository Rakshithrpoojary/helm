    # canary:
    #   canaryService: frontend-preview
    #   stableService: frontend-active
    #   trafficRouting:
    #     alb:
    #       ingress: mainlb
    #       servicePort: 80
    #   steps:
    #     - setWeight: 20
    #     - pause: {}
    #     - setWeight: 50
    #     - pause: {}        
    #     - setWeight: 100