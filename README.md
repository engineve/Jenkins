Continuous Integration

    integrating regularly helps to detect errors quickly and make changes small(easy to troubleshoot)
    when merging all features at once, it can make problems right before service release

    Pull Request -> tests(linting) -> Build -> Merge


Continuous Delivery

    the practice of keeping your code base deployable at any point
    small release batch(new patches, versions)

    Pipeline

        Pull Request -> tests(linting) -> Build -> Merge -> Acceptance Test -> Manual Deployment(to Production)


Continuous Deployment

    Continuous Delivery + Automatic Deployment

    Pipeline

        Pull Request -> tests(linting) -> Build -> Merge -> Acceptance Test(auto) -> Automatic Deployment(to Production)