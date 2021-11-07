---
id: 898
title: 'n'
date: 2021-07-23T15:41:03+00:00
author: Admin
layout: revision
guid: http://jayedrafi.com/?p=898
permalink: /?p=898
---
<img width="150" height="150" src="http://jayedrafi.com/wp-content/uploads/2021/07/My-Post-3-150x150.png" alt="" loading="lazy" srcset="http://jayedrafi.com/wp-content/uploads/2021/07/My-Post-3-150x150.png 150w, http://jayedrafi.com/wp-content/uploads/2021/07/My-Post-3-300x300.png 300w, http://jayedrafi.com/wp-content/uploads/2021/07/My-Post-3-1024x1024.png 1024w, http://jayedrafi.com/wp-content/uploads/2021/07/My-Post-3-768x768.png 768w, http://jayedrafi.com/wp-content/uploads/2021/07/My-Post-3.png 1080w" sizes="(max-width: 150px) 100vw, 150px" />

## Software Development

## Name Processor

## README

This software is designed and useful for real-life office work where people need to convert text format from spreadsheets. I made this while doing a database project at work where I needed to format tons of names and addresses and put them into the website. And it made my work more efficient as I did not need to spend time typing those data. Anyway, it takes input from the user and returns like the following example.

**Input:** STEpHen haWking  
**Output:** Stephen Hawking

<a target="_blank" rel="noopener"><br /> Cloud-download-alt<br /> </a>  
<a target="_blank" rel="noopener"><br /> Github<br /> </a>

## <code/>

&nbsp; import java.util.Scanner;&nbsp;

&nbsp; public class NameProcessor&nbsp;

&nbsp; {

&nbsp; public static void main(String args[])

&nbsp; {

&nbsp; Scanner scan = new Scanner(System.in);

&nbsp; String name = scan.nextLine();

&nbsp; String[] splitName = name.split(&#8221; &#8220;);

&nbsp; String output = &#8220;&#8221;;

&nbsp; int endPoint = splitName.length;

&nbsp; int i = 0;

&nbsp; while(i<endPoint)

&nbsp; {

&nbsp; String process = &#8220;&#8221;;

&nbsp; process += splitName[i].charAt(0);

&nbsp; process = process.toUpperCase();

&nbsp; String lower = &#8220;&#8221;;

&nbsp; for(int j=1; j<splitName[i].length(); j++)

&nbsp; {

&nbsp; lower+=splitName[i].charAt(j);

&nbsp; }

&nbsp; process+=lower.toLowerCase()+&#8221; &#8220;;

&nbsp; output+=process+&#8221; &#8220;;

&nbsp; process=&#8221;&#8221;;

&nbsp; lower = &#8220;&#8221;;

&nbsp; i++;

&nbsp; }

&nbsp; System.out.println(output);

&nbsp; }

&nbsp; }

## Services

  * Web Development
  * Software Development
  * UI/UX Design

## Get in touch

<a target="_blank" rel="noopener"><br /> Linkedin<br /> </a>  
<a target="_blank" rel="noopener"><br /> Github<br /> </a>  
<a target="_blank" rel="noopener"><br /> Behance<br /> </a>  
<a target="_blank" rel="noopener"><br /> Instagram<br /> </a>

  * jayedrafi@outlook.com