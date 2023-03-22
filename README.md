#System Resources:

- Memory usage percentage: {vm.memory.pools..usage} (Operation Center and Controller)

- CPU usage percentage: {system.cpu.load} (Operation Center and Controller)

- Disk usage: {disk-space} (Operation Center and Controller)

- File Descriptor Ratio (e.g. >75%): {vm.file.descriptor.ratio} (Operation Center and Controller)

#Platform:

- Operations center and managed controller response time: {http.requests} (Operation Center and Controller)

- Remaining Build node instances: {jenkins.executor.free.value} (Operation Center and Controller)

- Remaining Controller instances: {operations-center.jenkins.count.value}  (Operation Center)

- Good http request ratio (e.g. < 90%): {http.responseCodes.ok/http.requests} (Operation Center and Controller)

- Controllers online ratio (e.g. < 50%): {operations-center.jenkins.online.ratio} (Operation Center)

- Plugin updates available (e.g. > 10): {jenkins.plugins.withUpdate} (Operation Center and Controller)

#Workload:

- Job queue length (e.g. > 10 over 5 minutes): {jenkins.queue.size.value} (Controller)

- Job success ratio (e.g. < 50%): {jenkins.runs.success/jenkins.runs.total} (Operation Center and Controller)


