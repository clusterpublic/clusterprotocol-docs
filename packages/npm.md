# npm

Based on the information provided, I can help you generate a GitBook documentation template for the ClusterArena TypeScript library. Here is a structured format for your documentation:

## ClusterArena

ClusterArena is a TypeScript library that provides easy access to the Cluster Arena API. It allows you to manage jobs, add new jobs, and fetch job details seamlessly.

### Table of Contents

1. [Installation](npm.md#installation)
2. [Configuration](npm.md#configuration)
3. [Usage](npm.md#configuration)
   * [Initializing ClusterArena](npm.md#initializing-clusterarena)
   * [Fetching Jobs](npm.md#fetching-jobs)
   * [Adding a Job](npm.md#adding-a-job)
   * [Fetching Job Details](npm.md#fetching-job-details)
4. [Error Handling](npm.md#error-handling)

### Installation

To install the ClusterArena package, run the following command:

```bash
npm install @clusterprotocol/arena
```

### Configuration

Before using the ClusterArena library, you need to set up your API key. You can do this by setting the `CLUSTER_ARENA_API_KEY` environment variable or passing the API key directly when initializing the library.

### Usage

#### Initializing ClusterArena

To use ClusterArena, first import the library and create an instance of the ClusterArena class:

```typescript
1 import ClusterArena from '@clusterprotocol/arena';
2 const clusterArena = new ClusterArena('your-api-key-here');
```

Alternatively, you can set the `CLUSTER_ARENA_API_KEY` environment variable and initialize without passing the API key.

#### Fetching Jobs

To fetch all jobs, use the `getJobs` method:

```typescript
1 async function fetchJobs() {
2    try {
3        const jobs = await clusterArena.getJobs();
4        console.log('Jobs:', jobs);
5    } catch (error) {
6        console.error('Error fetching jobs:', error.message);
7    }
8 }
9 fetchJobs();
10
```

#### Adding a Job

To add a new job, use the `addJob` method. The job data must include a title and description:

```typescript
1 async function addNewJob() {
2    const jobData = {
3        model_id: 'meta/Meta-Llama-3-8B-Instruct',
4        input: {
5            prompt: "Write a poem in less than 3 lines.",
6            min_tokens: 100,
7            max_tokens: 512
8        }
9        // Add more fields as needed
10    };
11    try {
12        const newJob = await clusterArena.addJob(jobData);
13        console.log('New Job Added:', newJob);
14    } catch (error) {
15        console.error('Error adding job:', error.message);
16    }
17 }
18 addNewJob();
19
```

#### Fetching Job Details

To fetch details of a specific job, use the `getJobDetails` method and pass the job ID:

```typescript
1 async function fetchJobDetails(jobId: string) {
2    try {
3        const jobDetails = await clusterArena.getJobDetails(jobId);
4        console.log('Job Details:', jobDetails);
5    } catch (error) {
6        console.error('Error fetching job details:', error.message);
7    }
8 }
9 fetchJobDetails('job-id-here');
10
```

### Error Handling

The ClusterArena library throws errors when API requests fail or when invalid data is provided. Make sure to handle these errors appropriately in your application:

```typescript
1 try {
2    // Your code here
3} catch (error) {
4    console.error('An error occurred:', error.message);
5}
6
```

This template provides a structured outline for your GitBook documentation based on the information about the ClusterArena TypeScript library. Feel free to customize and expand upon it further as needed.
