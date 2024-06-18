
<h1>Components of Amazon EC2</h1>

1. **Instances**:
   
   - Virtual servers running applications.
     
   - Types include General Purpose, Compute Optimized, Memory Optimized, Storage Optimized, and Accelerated Computing.
     

2. **AMIs (Amazon Machine Images)**:
   
   - Pre-configured templates for instances that include the operating system and additional software.
     
   - Can be customized and saved for reuse.
     

3. **Instance Types**:
   
   - **General Purpose**: Balanced CPU, memory, and storage (e.g., t3, m5).
     
   - **Compute Optimized**: High CPU-to-memory ratio (e.g., c5, c6g).
     
   - **Memory Optimized**: High memory-to-CPU ratio (e.g., r5, x1).
     
   - **Storage Optimized**: High, sequential read and write access to large data sets (e.g., i3, d2).
     
   - **Accelerated Computing**: Hardware accelerators, or co-processors (e.g., p3, g4).
     

4. **Security Groups and Network ACLs**:
   
   - **Security Groups**: Act as a virtual firewall for instances to control inbound and outbound traffic.
     
   - **Network ACLs**: Act as a firewall for controlling traffic in and out of subnets.
     

5. **Elastic IP Addresses**:
    
   - Static, public IP addresses that can be associated with EC2 instances.
     

6. **Placement Groups**:
    
   - Logical grouping of instances within a single Availability Zone to enable low-latency network performance.
     
