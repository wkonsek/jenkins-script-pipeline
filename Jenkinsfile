
stage('Stage Name Here') {
    parallel (
        'Step 1': {
            node('docker'){
                sh 'echo "OS info: $(cat /etc/issue)"'
                sh 'echo "Hello from Docker ID: $(cat /proc/self/cgroup | head -1 | tr --delete ‘10:memory:/docker/’)"'
            }
        }, 
        'Step 2': {
            node('docker'){
                sh 'echo "OS info: $(cat /etc/issue)"'
                sh 'echo "Hello from Docker ID: $(cat /proc/self/cgroup | head -1 | tr --delete ‘10:memory:/docker/’)"'}
        }, 
        'Step 3': {
            node('docker'){
                sh 'echo "OS info: $(cat /etc/issue)"'
                sh 'echo "Hello from Docker ID: $(cat /proc/self/cgroup | head -1 | tr --delete ‘10:memory:/docker/’)"'}
        }, 
        'Step 4': {
            node('docker'){
                sh 'echo "OS info: $(cat /etc/issue)"'
                sh 'echo "Hello from Docker ID: $(cat /proc/self/cgroup | head -1 | tr --delete ‘10:memory:/docker/’)"'}
        }, 
        'Step 5': {
            node('docker'){
                sh 'echo "OS info: $(cat /etc/issue)"'
                sh 'echo "Hello from Docker ID: $(cat /proc/self/cgroup | head -1 | tr --delete ‘10:memory:/docker/’)"'}
        }
    )
}  
